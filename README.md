<h1 style="font-size: 34px;"><b>🔧 IOC Toolkit</b></h1>

<h2 style="font-size: 28px;"><b>📘 Overview</b></h2>

This repository is a growing collection of lightweight security utilities designed to support analysts, incident responders, and threat‑intelligence workflows. Each tool focuses on a specific operational task — such as defanging IOCs, checking IP addresses against blacklist services, enriching indicators, or automating repetitive analysis steps.

The goal is to provide simple, portable, and analyst‑friendly scripts that can be used independently or combined into larger workflows. As the toolkit expands, additional folders, tools, and documentation will be added to support a wide range of defensive use cases.

---

<h2 style="font-size: 28px;"><b>📁 Repository Structure</b></h2>

- **🛠️ IOC-Defanger/**  
  Tools for safely defanging URLs, domains, IPs, emails, and file paths.

- **🌐 IP-Reputation-Checker/**  
  Utility for checking the reputation of IP addresses using AbuseIPDB. Supports bulk IP lookups with simple configuration via API key and input file path.

➡️ **🧰 Future Tools/**  
Additional utilities will be added as the toolkit grows.

Each folder includes its own README and script files.

---

<h2 style="font-size: 28px;"><b>🎯 Purpose</b></h2>

This repository aims to:

- Provide safe, reliable utilities for handling and transforming Indicators of Compromise  
- Support enrichment and validation workflows for IPs, domains, URLs, and more  
- Offer modular tools that can be used individually or integrated into pipelines  
- Keep scripts simple, transparent, and easy to modify  
- Serve as a scalable toolkit for blue‑team and threat‑intel operations  

---

<h2 style="font-size: 28px;"><b>🚀 Usage</b></h2>

Each tool includes its own usage instructions inside its folder.  
Most scripts require:

- A text file containing input data  
- Editing the script to point to the full path of that file  
- Running the script in the appropriate environment (Batch, PowerShell, etc.)

Refer to the tool‑specific README for details.

---

<h2 style="font-size: 28px;"><b>📝 Notes</b></h2>

- No external dependencies unless stated in the tool’s folder  
- Designed for practical, real‑world analyst workflows  
- Additional tools and improvements will be added over time
