# vulnerbility-scaning

Nessus Essentials (Windows/Linux/macOS):

Register for a free activation key on the Tenable site.

Download the installer (e.g. Nessus-<version>.deb for Debian/Ubuntu or .rpm or Windows.msi).

Install and start the service. Access the web UI at https://localhost:8834.

2. Configure Scan Target
Launch the scanning tool’s web interface.

Create a new scan task:

Target: 127.0.0.1 (localhost) or your local IP (e.g. 192.168.x.x).

3. Start a Full Vulnerability Scan
Choose a comprehensive scan profile:

OpenVAS: “Full and fast”

Nessus: “Basic Network Scan” or equivalent

Begin the scan.

4. Wait for Scan Completion
Monitor progress in the UI.

Expect scan duration: 30 to 60 minutes depending on system size.

5. Review Vulnerability Report
Export the results upon completion (HTML/PDF/CSV).

Sort or filter by severity to identify critical/high findings.

6. Research Fixes & Mitigations
For each critical/high vulnerability:

Record the CVE identifier and severity.

Visit reputable sources (e.g., vendor advisories, CVE database).

Note down recommended patches, configuration changes, or mitigations.

7. Document Critical Vulnerabilities
Create a summary table like below:

CVE	Severity	Description	Remediation Steps
CVE-20xx-xxxx	Critical	Description of the vulnerability.	1. Apply patch KB123456
2. Enable secure settings...
