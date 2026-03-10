### **Nikto Vulnerability Scanning**

#### **Objective**

The purpose of this task was to scan a web server for possible security weaknesses using the **Nikto** vulnerability scanning tool.

#### **Tool Used**

* **Nikto** – a tool designed to detect vulnerabilities and misconfigurations in web servers.

#### **Target**

* Localhost web server / testphp.vulnweb.com

#### **Procedure**

1. Nikto was installed using the **APT** package manager.
2. A vulnerability scan was performed on the selected web server.
3. The scan results were saved in a file named **nikto_scan_results.txt**.
4. The results were reviewed to identify any potential security issues.

#### **Observations**

* The server revealed certain information that could be useful to attackers.
* Some important security headers were not configured.
* A few files and server settings appeared to be potentially insecure.

#### **Conclusion**

The scan performed by Nikto revealed several vulnerabilities and configuration issues on the web server. This demonstrates that Nikto is a useful tool for conducting basic security assessments of web servers.

