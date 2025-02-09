
# Red Stealer

## Scenario
You are part of the Threat Intelligence team in the SOC (Security Operations Center). An executable file has been discovered on a colleague's computer, and it's suspected to be linked to a Command and Control (C2) server, indicating a potential malware infection.

Your task is to investigate this executable by analyzing its hash. The goal is to gather and analyze data beneficial to other SOC members, including the Incident Response team, to respond to this suspicious behavior efficiently.

## Questions
SHA256 - 248fcc901aff4e4b4c48c91e4d78a939bf681c9a1bc24addc3551b32768f907b
All questions were answered with VirusTotal, MalwareBazaar, ThreatFox, and ANY.RUN.

### Categorizing malware enables a quicker and easier understanding of its distinct behaviors and attack vectors. What is the category of the identified malware?
<img src="https://i.imgur.com/quriWb2.png" width=80% height=80%>

### Clearly identifying the name of the malware file improves communication among the SOC team. What is the file name associated with this malware?
<img src="https://i.imgur.com/quriWb2.png" width=80% height=80%>

### Knowing the exact timestamp of when the malware was first observed can help prioritize response actions. Newly detected malware may require urgent containment and eradication compared to older, well-documented threats. What is the UTC timestamp of the malware's first submission to VirusTotal?
<img src="https://i.imgur.com/9U6m8Be.png" width=80% height=80%>

### Understanding the techniques used by malware helps in strategic security planning. What is the MITRE ATT&CK technique ID for the malware's data collection from the system before exfiltration?
<img src="https://i.imgur.com/V1oRusv.png" width=80% height=80%>

### Following execution, what domain name resolution is performed by the malware?
<img src="https://i.imgur.com/JvoIWgt.png" width=80% height=80%>

### Once the malicious IP addresses are identified, network security devices such as firewalls can be configured to block traffic to and from these addresses. Can you provide the IP address and destination port the malware communicates with?
<img src="https://i.imgur.com/XOSSy0n.png" width=80% height=80%>

### YARA rules are designed to identify specific malware patterns and behaviors. What's the name of the YARA rule created by "Varp0s" that detects the identified malware?
<img src="https://i.imgur.com/uibrBbF.png" width=80% height=80%>

### Understanding which malware families are targeting the organization helps in strategic security planning for the future and prioritizing resources based on the threat. Can you provide the different malware alias associated with the malicious IP address according to ThreatFox?
<img src="https://i.imgur.com/tD4cb0X.png" width=80% height=80%>

### By identifying the malware's imported DLLs, we can configure security tools to monitor for the loading or unusual usage of these specific DLLs. Can you provide the DLL utilized by the malware for privilege escalation?
<img src="https://i.imgur.com/bWxBiDL.png" width=80% height=80%>
