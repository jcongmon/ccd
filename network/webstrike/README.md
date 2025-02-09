# WebStrike

## Scenario
A suspicious file was identified on a company web server, raising alarms within the intranet. The Development team flagged the anomaly, suspecting potential malicious activity. To address the issue, the network team captured critical network traffic and prepared a PCAP file for review. Your task is to analyze the provided PCAP file to uncover how the file appeared and determine the extent of any unauthorized activity.

## Questions
All questions were solved using Wireshark.

### Identifying the geographical origin of the attack helps in implementing geo-blocking measures and analyzing threat intelligence. From which city did the attack originate?
<img src="https://i.imgur.com/7hADJQg.png" width=50% height=50%>

### Knowing the attacker's User-Agent assists in creating robust filtering rules. What's the attacker's User-Agent?
<img src="https://i.imgur.com/wTryMSm.png" width=80% height=80%>

### We need to determine if any vulnerabilities were exploited. What is the name of the malicious web shell that was successfully uploaded?
<img src="https://i.imgur.com/eL0Wy1s.png" width=80% height=80%>

### Identifying the directory where uploaded files are stored is crucial for locating the vulnerable page and removing any malicious files. Which directory is used by the website to store the uploaded files?
<img src="https://i.imgur.com/eL0Wy1s.png" width=80% height=80%>

### Which port, opened on the attacker's machine, was targeted by the malicious web shell for establishing unauthorized outbound communication?
<img src="https://i.imgur.com/53jq1sK.png" width=80% height=80%>

### Recognizing the significance of compromised data helps prioritize incident response actions. Which file was the attacker attempting to exfiltrate?
<img src="https://i.imgur.com/mUCLHWo.png" width=80% height=80%>


