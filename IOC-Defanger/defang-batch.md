@echo off
setlocal enabledelayedexpansion

set "input=C:\Users\Raiz3n\Downloads\IOCdefang\ioc_list.txt"

for /f "usebackq delims=" %%A in ("%input%") do (
    set "line=%%A"

    rem Replace http with hxxp
    set "line=!line:http://=hxxp[://]!"

    rem Replace https with hxxps
    set "line=!line:https://=hxxps[://]!"

    rem Replace . with [.] (but keep protocol intact)
    set "line=!line:.=[.]!"


    rem ============================
    rem Email Defang Logic
    rem ============================

    rem Replace @ with [@]
    set "line=!line:@=[@]!"


    rem ============================
    rem File Path Defang Logic
    rem ============================

    rem Replace : with [:]
    set "line=!line::=[:]!"

    rem Replace :\ with [:\]
    set "line=!line::\=[:\]!"

    echo !line!
)

endlocal
pause
