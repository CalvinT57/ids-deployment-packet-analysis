# IDS Deployment & Packet Analysis (Suricata)

## Overview
This project demonstrates deploying and validating a network Intrusion Detection System (IDS) using **Suricata** on Ubuntu. Attack and reconnaissance traffic was generated from a **Kali Linux** host and analyzed through Suricata alert logs.

## Lab Environment
- **IDS Sensor:** Ubuntu 24.04 with Suricata
- **Attacker:** Kali Linux
- **Hypervisor:** VMware Fusion
- **Network:** Isolated host-only lab network

## Tools Used
- Suricata
- Kali Linux
- Nmap
- Ubuntu Linux
- VMware Fusion

## Project Steps
1. Installed and verified Suricata build features and packet capture support.
2. Identified the correct monitoring interface on the IDS sensor.
3. Updated and enabled Emerging Threats Open rules.
4. Started Suricata in IDS mode and validated rule loading.
5. Generated reconnaissance traffic from Kali Linux.
6. Confirmed IDS alert generation using Suricata logs.

## Evidence

### Suricata Build Verification
![Suricata Build](images/Screenshot_02C_Suricata_Build_Info.png)

### Sensor Interface Configuration
![Interface](images/Screenshot_03_Sensor_Interface_IP.png)

### IDS Running with Rules Loaded
![Suricata Running](images/Screenshot_04D_Suricata_Running_With_Rules.png)

### Kali to IDS Connectivity
![Ping](images/Screenshot_05_Ping_Kali_to_IDS.png)

### Reconnaissance Traffic (Nmap Scan)
![Nmap Scan](images/Screenshot_06_Nmap_Scan_Attack_Traffic.png)

### Suricata Alert Evidence
![Alert](images/Screenshot_07_Suricata_Alert_fastlog.png)

## Resume Highlights
- Deployed and configured a Suricata IDS sensor to monitor live network traffic.
- Simulated reconnaissance activity from a Kali Linux host using Nmap.
- Validated IDS alert generation and reviewed Suricata fast.log entries.
- Demonstrated SOC Tier 1 workflows including sensor validation, rule management, and alert triage.
