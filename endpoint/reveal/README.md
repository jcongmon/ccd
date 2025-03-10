# Reveal

## Scenario
You are a forensic investigator at a financial institution, and your SIEM flagged unusual activity on a workstation with access to sensitive financial data. Suspecting a breach, you received a memory dump from the compromised machine. Your task is to analyze the memory for signs of compromise, trace the anomaly's origin, and assess its scope to contain the incident effectively.

## Questions
All questions were solved using Volatility 3.

### Identifying the name of the malicious process helps in understanding the nature of the attack. What is the name of the malicious process?
<img src="https://i.imgur.com/kRWFXPz.png" width=80% height=80%>

### Knowing the parent process ID (PPID) of the malicious process aids in tracing the process hierarchy and understanding the attack flow. What is the parent PID of the malicious process?
<img src="https://i.imgur.com/qftcvS1.png" width=80% height=80%>

### Determining the file name used by the malware for executing the second-stage payload is crucial for identifying subsequent malicious activities. What is the file name that the malware uses to execute the second-stage payload?
<img src="https://i.imgur.com/qftcvS1.png" width=80% height=80%>

### Identifying the shared directory on the remote server helps trace the resources targeted by the attacker. What is the name of the shared directory being accessed on the remote server?
<img src="https://i.imgur.com/qftcvS1.png" width=80% height=80%>

### What is the MITRE ATT&CK sub-technique ID that describes the execution of a second-stage payload using a Windows utility to run the malicious file?
<img src="https://i.imgur.com/btsx0Xs.png" width=80% height=80%>

### Identifying the username under which the malicious process runs helps in assessing the compromised account and its potential impact. What is the username that the malicious process runs under?
<img src="https://i.imgur.com/mKh8HCZ.png" width=80% height=80%>

### Knowing the name of the malware family is essential for correlating the attack with known threats and developing appropriate defenses. What is the name of the malware family?
<img src="https://i.imgur.com/ymM3bXU.png" width=80% height=80%>

