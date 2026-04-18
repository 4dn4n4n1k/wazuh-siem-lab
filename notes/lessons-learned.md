# 🧠 Lessons Learned

## 📌 Overview
This project provided hands-on experience in deploying and managing a cloud-based SIEM solution using Wazuh. It helped bridge the gap between theoretical cybersecurity concepts and real-world implementation.

---

## 🔍 Key Learnings

### 1. SIEM Deployment in a Cloud Environment
I learned how to deploy a full SIEM stack (Wazuh Manager, Indexer, and Dashboard) on a cloud server. This included configuring system resources, networking, and ensuring service availability.

---

### 2. Importance of Proper Configuration
Correct firewall configuration was critical for communication between the Wazuh server and agents. Misconfigured ports or network settings can completely block data flow.

---

### 3. Endpoint Monitoring and Visibility
By connecting multiple agents (Ubuntu and Kali Linux), I understood how endpoint logs are collected and centralized. This provided visibility into system activity across different machines.

---

### 4. Real-Time Threat Detection
Through simulated attacks such as privilege escalation and failed login attempts, I observed how Wazuh detects and generates alerts based on predefined rules. This reflects how real Security Operations Centers (SOC) monitor threats.

---

### 5. Log Analysis and Alert Interpretation
Each alert includes rule IDs, severity levels, and detailed descriptions. Learning how to interpret these alerts is essential for identifying suspicious behavior and responding effectively.

---

### 6. Challenges Faced
- OS compatibility issues during installation
- Incorrect script downloads and execution errors
- Agent connection troubleshooting
- Understanding Wazuh alert structure

These challenges helped improve problem-solving and debugging skills.

---

### 7. Practical Understanding of Security Monitoring
This project demonstrated how attackers’ actions (e.g., brute-force attempts or privilege escalation) leave traces in logs, and how SIEM tools can detect them.

---

## 🚀 Future Improvements

- Add Windows agent for broader monitoring
- Implement custom Wazuh detection rules
- Integrate threat intelligence feeds
- Map detections to MITRE ATT&CK framework

---

## 🎯 Conclusion

This project significantly improved my practical understanding of SIEM systems, log analysis, and threat detection. It provided a strong foundation for working in a SOC environment and handling real-world cybersecurity scenarios.