# DanaBot

## Scenario
The SOC team has detected suspicious activity in the network traffic, revealing that a machine has been compromised. Sensitive company information has been stolen. Your task is to use Network Capture (PCAP) files and Threat Intelligence to investigate the incident and determine how the breach occurred.

## Questions
All questions were solved using Wireshark.

### Which IP address was used by the attacker during the initial access?
<img src="https://i.imgur.com/T3urMFg.png" width=80% height=80%>

### What is the name of the malicious file used for initial access?
<img src="https://i.imgur.com/T3urMFg.png" width=80% height=80%>

### What is the SHA-256 hash of the malicious file used for initial access?
Exported the HTTP object of frame 11.
<img src="https://i.imgur.com/i0FTiFm.png" width=80% height=80%>

### Which process was used to execute the malicious file?
Referenced the SHA256 hash on any.run.
<img src="https://i.imgur.com/9MNcFpq.png" width=80% height=80%>

### What is the file extension of the second malicious file utilized by the attacker?
<img src="https://i.imgur.com/v3HvK49.png" width=80% height=80%>

### What is the MD5 hash of the second malicious file?
Exported the HTTP object of frame 9952.
<img src="https://i.imgur.com/nbbKOJv.png" width=80% height=80%>

