<h1 style="font-size: 30px;"><b>IOC Defanging Toolkit</b></h1>

A lightweight and flexible toolkit for safely defanging Indicators of Compromise (IOCs). This project provides simple, portable methods for neutralizing URLs, domains, IPs, emails, file paths, and other indicators so they can be shared or analyzed without risk of accidental activation. The toolkit is designed to grow over time with additional scripts and approaches.

---

<h2 style="font-size: 24px;"><b>📁 Repository Structure</b></h2>

- README.md — Project overview  
- script.md — Full defanging script  
- ioc_list.txt — Example IOC list (optional)  
- Additional methods and scripts will be added over time

---

<h2 style="font-size: 24px;"><b>📥 Input Requirements</b></h2>

This toolkit requires your IOC data to be stored in a separate text file.  
Before running any script, you must edit the script and update the full path to your IOC text file.

Example of what you will update inside the script (shown here as plain text to avoid escaping issues in markdown fences):

`set "input=Filepath"`

Replace the "Filepath" with the location of your own IOC list.

---

<h2 style="font-size: 24px;"><b>🔧 What This Toolkit Does</b></h2>

This project focuses on transforming potentially harmful indicators into safe, non‑clickable formats. Examples include:

- Neutralizing URLs and domains  
- Defanging IP addresses  
- Sanitizing email addresses  
- Making file paths safe to share  
- Preventing accidental resolution or execution of IOCs  

Each method is designed to be simple, transparent, and easy to integrate into analyst workflows.

---

<h2 style="font-size: 24px;"><b>🚀 Usage Overview</b></h2>

1. Create or edit your IOC text file  
2. Update the script with the full path to that file  
3. Run the script  
4. Review or export the safely defanged output  

Detailed usage instructions are included in each script’s dedicated markdown file.

---

<h2 style="font-size: 24px;"><b>📌 Notes</b></h2>

- No external dependencies  
- Designed for analysts, responders, and threat intelligence workflows  
- Future updates will include additional defanging techniques and script types
