<h1 style="font-size: 30px;">
  🌐 IP‑Reputation‑Checker_AbuseIPDB
</h1>

<p style="font-size: 16px;">
  <b>IP‑Reputation‑Checker</b> is a lightweight enrichment utility designed to perform bulk IP reputation lookups 
  using the AbuseIPDB API. It enables analysts to quickly assess the risk level of multiple IP addresses during 
  investigations, threat hunting, and incident response workflows.
</p>

<h2 style="font-size: 22px;">⚙️ Features</h2>
<ul style="font-size: 16px;">
  <li>Bulk reputation lookups for large IP lists.</li>
  <li>Queries AbuseIPDB for confidence scores, abuse categories, and historical reports.</li>
  <li>Outputs clean, analyst‑ready results for triage and reporting.</li>
  <li>Lightweight, portable, and easy to run in any Windows environment.</li>
</ul>

<h2 style="font-size: 22px;">📄 Usage Overview</h2>
<p style="font-size: 16px;">
  Add your AbuseIPDB API key to the script, specify the path to your IP list, and run the tool to generate 
  enriched reputation results. Designed for quick operational use with minimal setup.
</p>

<h2 style="font-size: 22px;">📝 How to Use</h2>
<p style="font-size: 16px;">
  <b>Bulk IP check using AbuseIPDB:</b><br><br>
  • Download <b>IP‑Reputation‑Checker_AbuseIPDB</b> to any folder on your system.<br>
  • Open the file in Notepad and locate <b>line 4</b>, which contains:<br>
  &nbsp;&nbsp;&nbsp;&nbsp;<b>set "API_KEY=&lt;Paste API here inside the quotes&gt;"</b><br>
  • Replace <b>&lt;Paste API here inside the quotes&gt;</b> with your actual AbuseIPDB API key, keeping it <b>inside the quotation marks</b>.<br>
  • On <b>line 5</b>, provide the <b>full file path</b> to the file containing your list of IP addresses, one IP per line, and ensure the path is placed <b>inside the quotes</b>.<br>
  • Save the file after adding your API key and IP list path.<br>
  • Run the script by simply double‑clicking <b>IP‑Reputation‑Checker_AbuseIPDB</b>.
</p>

<h2 style="font-size: 22px;">🧰 Ideal For</h2>
<ul style="font-size: 16px;">
  <li>Threat intelligence enrichment</li>
  <li>Incident response triage</li>
  <li>Detection engineering validation</li>
  <li>Bulk IOC processing workflows</li>
</ul>
