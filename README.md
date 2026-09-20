# nightwatch-linux-incident-investigation-Hands-ON-
## Hands-on Cybersecurity Investigations

Completed multiple hands-on cybersecurity investigations in controlled lab environments, covering key SOC, incident response, network security, threat intelligence, and security monitoring workflows.

### 1. Linux Incident Investigation — The Nightwatch Incident

Investigated a simulated compromised Linux host using Kali Linux and Docker. The investigation focused on identifying signs of compromise, unauthorized access, persistence mechanisms, and suspicious system activity.

Activities included:
- Analyzing authentication logs and failed login attempts
- Investigating suspicious local accounts and identifying a UID 0 backdoor account
- Examining suspicious processes running with elevated privileges
- Investigating suspicious listening network connections and ports
- Analyzing cron jobs for persistence
- Investigating suspicious scripts and files
- Identifying suspicious SUID binaries and examining file permissions
- Investigating recently modified system files
- Calculating SHA-256 hashes of suspicious artifacts
- Documenting investigation findings and potential indicators of compromise

### 2. Windows Incident Investigation — The Outpost Incident

Performed a hands-on investigation of a simulated compromised Windows environment. The investigation involved Windows authentication activity, suspicious accounts, PowerShell execution, scheduled-task persistence, and suspicious processes.

Activities included:
- Investigating Windows authentication events
- Analyzing failed and successful logon activity
- Identifying suspicious local accounts and administrator privileges
- Investigating suspicious PowerShell activity
- Analyzing process creation events
- Investigating scheduled tasks used for persistence
- Examining suspicious scripts and hidden files
- Investigating suspicious network listener activity
- Analyzing file hashes and security artifacts
- Mapping observed activity to relevant attack techniques

### 3. SIEM Alert Triage Investigation

Performed SOC-style alert triage using simulated security alerts and log data.

Activities included:
- Reviewing security alerts and associated event data
- Identifying suspicious authentication and brute-force activity
- Distinguishing between True Positive, False Positive, and Benign Positive alerts
- Assessing alert severity and potential impact
- Investigating supporting log evidence
- Applying incident response concepts to security alerts
- Determining appropriate escalation requirements
- Documenting findings in a structured SOC ticket format
- Applying NIST Incident Response lifecycle concepts
- Using playbook-driven investigation and response workflows

### 4. Phishing & BEC Investigation

Investigated a simulated phishing and Business Email Compromise scenario involving a malicious email requesting a financial wire transfer.

Activities included:
- Examining email headers and message metadata
- Analyzing sender and recipient information
- Investigating suspicious email infrastructure
- Reviewing SPF, DKIM, and DMARC authentication results
- Identifying indicators of phishing and potential email spoofing
- Analyzing the social-engineering characteristics of the message
- Identifying potential Business Email Compromise indicators
- Extracting relevant indicators of compromise
- Assessing the potential impact of the malicious email
- Documenting findings as part of a phishing investigation

### 5. Network Security Investigation — Wireshark

Performed a network investigation using Wireshark and a simulated network capture to identify suspicious network activity.

Activities included:
- Analyzing network traffic and packet captures
- Identifying internal and external hosts
- Investigating suspicious DNS queries and responses
- Identifying potential DNS beaconing behavior
- Analyzing TCP connection attempts and SYN scanning activity
- Investigating exposed and targeted ports
- Examining FTP authentication traffic
- Identifying suspicious external communication
- Differentiating between north-south and east-west traffic
- Applying networking and OSI model concepts during investigation
- Identifying indicators that could be used for further threat investigation

### 6. MITRE ATT&CK & Threat Intelligence Investigation

Applied MITRE ATT&CK and threat intelligence concepts to analyze adversary behavior and security indicators.

Activities included:
- Understanding adversary tactics, techniques, and procedures (TTPs)
- Differentiating between IOCs, IOAs, and TTPs
- Mapping observed suspicious activities to MITRE ATT&CK techniques
- Analyzing common attacker objectives and behaviors
- Identifying relevant indicators for investigation
- Understanding how threat intelligence supports SOC investigations
- Connecting observed activity with attacker tactics and techniques
- Using structured threat intelligence concepts to improve incident analysis

## Skills Demonstrated

Through these investigations, I developed practical exposure to:

- Security Operations Center (SOC) workflows
- Incident Response
- SIEM Alert Triage
- Log Analysis
- Linux Security Investigation
- Windows Security Investigation
- Authentication Analysis
- Process Investigation
- Persistence Detection
- Network Traffic Analysis
- Wireshark
- Phishing & BEC Investigation
- Email Header Analysis
- IOC Analysis
- MITRE ATT&CK
- Threat Intelligence
- File and Hash Analysis
- Security Event Investigation
- Incident Documentation and Reporting

All investigations were performed in controlled cybersecurity lab environments for educational and practical skill development.
