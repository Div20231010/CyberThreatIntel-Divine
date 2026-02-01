# CyberThreatIntel-Divine
This is an Enterprise Cyber Threat Intelligence project leveraging OPENCTI as the central intelligence platform and the ALIENVAULT OTX Connector for real-time threat data ingestion and analysis.

📌 **Project Overview**
CYBERINFINITI-CTI is a Cyber Threat Intelligence (CTI) initiative developed by Team 8 SOC to enhance the security resilience and risk management posture of **Cyberinfiniti Ltd**, an IT and cybersecurity services provider.

This project models how an internal CTI function operates within an enterprise setting — identifying, analyzing, and contextualizing cyber threats based on the organization’s operational landscape, industry focus, and geographic exposure. It utilizes **OpenCTI** as the central intelligence platform, securely deployed on AWS, and enriched with live threat data from **AlienVault OTX**, enabling the correlation of global threat indicators with tailored intelligence requirements.

The primary goal is to convert raw threat data into actionable, executive-ready intelligence that supports strategic, operational, and defensive decision-making. The assessment includes profiling threat actors, mapping sector-specific risks, and analyzing politically or criminally motivated campaigns, all aligned with established frameworks such as MITRE ATT&CK and the Diamond Model.

---

### Project Objective
- Evaluate the sector-specific cyber threat landscape impacting IT and cybersecurity enterprises  
- Examine national-level adversarial activity targeting organizational headquarters and operations  
- Profile recent victims, linked threat actors, and associated attack campaigns  
- Explore a politically motivated APT group engaged in significant operations  
- Convert technical threat intelligence into clear, actionable recommendations for executives
 ---

🏗️ Architecture & Deployment
The OpenCTI platform was deployed in a secure AWS cloud environment to reflect production-grade CTI operations.

Environment Details
Cloud Provider: AWS
Instance Type: EC2 (Ubuntu Server)
Deployment Model: Docker & Docker Compose
Intelligence Platform: OpenCTI
Threat Feed Integration: AlienVault OTX
Core Components

### openCTI API & web interface
-OpenCTI API & Web Interface
-Graph Database (STIX 2.1 Data Model)
-RabbitMQ (Message Queuing)
-Elasticsearch, Redis, MinIO
-AlienVault OTX Connector
This modular architecture enables scalable ingestion, correlation, and visualization of threat intelligence.
---

### Methodology
The assessment followed the Threat Intelligence Lifecycle:

- **Direction** – Established intelligence objectives aligned with organizational risk priorities  
- **Collection** – Gathered threat data through OpenCTI and AlienVault OTX integration  
- **Processing** – Standardized indicators, entities, and relational data for consistency  
- **Analysis** – Utilized structured analytical models to interpret findings  
- **Dissemination** – Delivered both analyst-focused and executive-level intelligence reports  

### Analytical Frameworks Applied
- Diamond Model of Intrusion Analysis  
- Cyber/Global Kill Chain methodology  
- MITRE ATT&CK framework  
- Timeline and Campaign-based analysis
---

### Industry Sector Focus
**Sector:** Information Technology & Cybersecurity (Managed Security Service Providers / IT Services)

Key Threat Categories identified from this project
- Ransomware operations and double-extortion tactics  
- State-backed espionage campaigns (APT activity)  
- Credential theft leading to lateral movement across networks  
- Covert data exfiltration techniques  

### Notable Threat Actors
- Akira Ransomware Group  
- APT17  
- POLONIUM
---

### National Threat Landscape
**Headquarters Location:** Nigeria  

### Assessed Threat Actors
- **Hilalrat (UNC788)** – A financially driven cybercrime group operating across West Africa  
- **Hoplight / APT38 (Lazarus Group)** – A state-sponsored adversary conducting large-scale financial cyber operations
---

### 🎯 Victim-Centric Threat Mapping

The project modeled realistic victim profiles by leveraging intelligence data curated within the OpenCTI platform. The analysis helped identify how specific threat actors select and exploit victims, enabling more precise threat attribution and risk prioritization.

Government Institutions
Healthcare Organizations
Defense Sector Entities
Each profile includes:

### Diamond Model Analysis
-Kill Chain Mapping
-MITRE ATT&CK technique alignment
-Detection & mitigation recommendations
---

### 🛡️ Politically Motivated Threat Actor Assessment

***Focused Threat Group:** Sandworm (APT44 / Seashell Blizzard)  
- Russia-aligned, state-sponsored threat actor  
- Notorious for destructive cyber operations and the use of wiper malware  
- Recent campaigns have targeted energy providers and critical infrastructure sectors  

### 🔍 Analyzed Campaigns
- Poland Energy Sector – December 2025  
- Ukrainian Government & Energy Sectors – 2025
---

### 🛡️ Detection & Mitigation Highlights

- Behavioral monitoring to identify credential misuse and lateral movement attempts  
- Continuous detection of living-off-the-land (LotL) techniques leveraged by adversaries  
- Visibility into DNS queries, proxy traffic, and encrypted command-and-control (C2) channels  
- Implementation of sector-specific defensive measures mapped to the MITRE ATT&CK framework

  ---
### 📊 Key Findings

- Credential theft continues to be the primary pathway for initial access  
- Ransomware groups and APT actors are increasingly overlapping in tools and intrusion techniques  
- Politically driven destructive operations are rising in both scale and frequency  
- Reuse of threats across multiple sectors amplifies supply-chain vulnerabilities

### 📚 Lessons Learned
Threat intelligence is most effective when aligned with business context
Automation and enrichment significantly improve analyst efficiency
Executive-ready reporting is critical for informed decision-making
CTI platforms like OpenCTI enable meaningful correlation across threats, victims, and campaigns
---

### 👥 Team Contributions

- Coordinated tasks and provided support to the team during the threat intelligence project  
- Assisted in the execution of analytical activities and overall collaboration  
- Contributed to the preparation of slides and executive-level reporting for presentations  

This project was carried out collaboratively by **Team 8** during the CyBlack Threat Intelligence Sprint.  

### References
-OpenCTI Documentation
-AlienVault Open Threat Exchange (OTX)
-MITRE ATT&CK Framework
-AWS, Docker & Ubuntu Documentation
---

### 🌍 Why This Project Matters

This repository highlights practical Cyber Threat Intelligence (CTI) skills essential for modern security operations, including:  

- Leveraging cloud infrastructure for scalable deployments  
- Implementing and managing CTI platforms  
- Profiling and assessing threat actors  
- Applying structured analytical frameworks to investigations  
- Producing executive-level intelligence reports for decision-makers  

It is designed to align with the core competencies expected of **SOC Analysts, Threat Intelligence Analysts, and Blue Team professionals**, serving as a realistic demonstration of CTI practices in action.  
