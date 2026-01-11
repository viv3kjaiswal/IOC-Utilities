@echo off
setlocal enabledelayedexpansion

set "input=Filepath"

for /f "usebackq delims=" %%A in ("%input%") do (
    set "line=%%A"

    rem ============================
    rem URL Defang Logic
    rem ============================

    rem Normalize protocols directly
    set "line=!line:https://=hxxps[:]//!"
    set "line=!line:http://=hxxp[:]//!"

    rem Replace dots
    set "line=!line:.=[.]!"

    rem ============================
    rem Email Defang Logic
    rem ============================

    rem Replace @ with [@]
    set "line=!line:@=[@]!"

    rem ============================
    rem File Path Defang Logic
    rem ============================

    rem Defang drive letter paths like C:\
    if "!line!" neq "!line::\=!" (
        set "line=!line::\=[:\]!"
    )

    echo !line!
)

endlocal
pause
