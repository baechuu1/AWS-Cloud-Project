
☁️ AWS Cloud Security Lab
📊 Project Highlights

☁️ AWS CloudTrail Log Analysis
🔍 API Activity Monitoring
🧠 Cloud Threat Detection & Investigation
📂 IAM & S3 Security Analysis
🧬 MITRE ATT&CK Mapping
⚔️ Cloud Attack Simulation (Attacker → Defender)

📌 Overview

This project is a hands-on Cloud Security Lab designed to simulate a real-world AWS account compromise and demonstrate detection and investigation using CloudTrail and Splunk.

Each attack scenario follows a structured workflow:

⚔️ Attack Simulation (API-based)
📥 CloudTrail Log Collection
🔍 Detection & Analysis (Splunk / CloudTrail)
🧬 MITRE ATT&CK Mapping
🛡️ Mitigation & Hardening
🧪 Lab Environment
Component	Description
🐉 Kali Linux	Attacker machine (AWS CLI)
☁️ AWS	Cloud environment
📊 Splunk SIEM	Log ingestion & analysis
📦 S3 Bucket	CloudTrail log storage
🔐 IAM	Identity & access control
⚔️ Attack Scenarios
Attack	Description	Status
🔑 Credential Compromise	Simulated exposed IAM access keys	✅ Completed
🔍 Cloud Reconnaissance	API enumeration via AWS CLI	✅ Completed
🔺 Privilege Escalation	IAM misconfiguration abuse	🔄 In Progress
🔁 Persistence	Backdoor IAM users / access keys	⏳ Planned
📂 S3 Exposure	Public bucket misconfiguration	⏳ Planned
📡 Cloud Activity Detection	Splunk-based detection & correlation	⏳ Planned
📂 Project Structure
aws-cloud-security-lab/
│
├── phases/
│   ├── initial-access-recon/
│   ├── privilege-escalation/
│   ├── persistence/
│   ├── s3-exposure/
│
├── detections/
│
├── mappings/
│
├── screenshots/
│
└── README.md
🎯 Objective

Build a practical understanding of how cloud attacks are executed and detected, focusing on AWS environments, IAM abuse, and API-based attacker behavior.

🧠 Key Concepts Demonstrated
Category	Skills
🔍 Detection	CloudTrail Analysis, SIEM Monitoring
🚨 Investigation	API Activity Analysis, Incident Triage
🧬 Threat Mapping	MITRE ATT&CK (Valid Accounts, Discovery)
🕵️ Analysis	IAM Abuse, AccessDenied Patterns
🛡️ Defense	Least Privilege, Logging & Monitoring
🚀 Roadmap
🔑 Credential Compromise Simulation
🔍 Cloud Reconnaissance (AWS CLI Activity)
🔺 IAM Privilege Escalation
🔁 Persistence via IAM Abuse
📂 S3 Public Exposure Detection
📡 Splunk Detection Engineering
⚠️ Disclaimer

This project is for educational purposes only. All activity is conducted in a controlled lab environment using personal AWS resources.
