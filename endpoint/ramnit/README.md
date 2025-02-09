# Ramnit

## Scenario
Our intrusion detection system has alerted us to suspicious behavior on a workstation, pointing to a likely malware intrusion. A memory dump of this system has been taken for analysis. Your task is to analyze this dump, trace the malware’s actions, and report key findings.

## Questions
All questions were solved using Volatility 3.

### What is the name of the process responsible for the suspicious activity?
<img src="https://i.imgur.com/6QDRw9W.png" width=80% height=80%>

### What is the exact path of the executable for the malicious process?
<img src="https://i.imgur.com/6QDRw9W.png" width=80% height=80%>

### Identifying network connections is crucial for understanding the malware's communication strategy. What IP address did the malware attempt to connect to?
<img src="https://i.imgur.com/yp3QTIZ.png" width=80% height=80%>

### To determine the specific geographical origin of the attack, Which city is associated with the IP address the malware communicated with?
<img src="https://i.imgur.com/ZAZyzAT.png" width=80% height=80%>

### Hashes serve as unique identifiers for files, assisting in the detection of similar threats across different machines. What is the SHA1 hash of the malware executable?
<img src="https://i.imgur.com/7fZvaKO.png" width=80% height=80%>
<img src="https://i.imgur.com/JnJnrkj.png" width=80% height=80%>

### Examining the malware's development timeline can provide insights into its deployment. What is the compilation timestamp for the malware?
<img src="https://i.imgur.com/0p2I3Ux.png" width=80% height=80%>

### Identifying the domains associated with this malware is crucial for blocking future malicious communications and detecting any ongoing interactions with those domains within our network. Can you provide the domain connected to the malware?
<img src="https://i.imgur.com/a32boGX.png" width=80% height=80%>
