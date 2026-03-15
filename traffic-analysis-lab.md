Malicious PowerShell Download Investigation

Platform
TryHackMe

Objective
Investigate network traffic to identify a malicious PowerShell download initiated through a phishing attack.

Scenario
A workstation clicked a phishing link which triggered an HTTP request to download a malicious PowerShell file.

Investigation Steps
1. Placed a network TAP between the firewall and router.
2. Captured network traffic.
3. Inspected HTTP GET request from internal host.
4. Analyzed HTTP response packet.
5. Identified malicious PowerShell script.

Key Findings
Source IP: 192.168.0.1  
Destination IP: 93.184.216.34  
Protocol: HTTP

Flag
THM{REDACTED}

Lessons Learned
Network traffic analysis helps detect malicious downloads triggered through phishing attacks.
