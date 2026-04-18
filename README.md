# 🔐 Wazuh SIEM Lab on DigitalOcean

## 📌 Overview
This project demonstrates a cloud-based SIEM (Security Information and Event Management) lab using Wazuh to monitor and detect security events across multiple endpoints.

## 🧱 Architecture
- Wazuh Server (DigitalOcean Ubuntu Droplet)
- Ubuntu Agent
- Kali Linux Agent

## ⚙️ Setup
- Deployed Wazuh using official installation script
- Configured firewall and networking
- Connected multiple agents

## 🔍 Attack Simulations
- Privilege escalation (sudo)
- Failed login attempts
- Brute-force attack using Hydra
- Command execution monitoring

## 📊 Results
Wazuh successfully detected:
- Unauthorized access attempts
- Suspicious command execution
- Authentication failures

## 🧠 Skills Demonstrated
- SIEM deployment
- Log analysis
- Threat detection
- Cloud security setup


## 🚀 Future Improvements
- Add Windows agent
- Integrate threat intelligence feeds
- Create custom detection rules
