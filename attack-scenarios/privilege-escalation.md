# 🔐 Privilege Escalation Detection

## 📌 Objective
To test whether Wazuh can detect privilege escalation attempts on a monitored system.

---

## 🧱 Environment
- Wazuh Server: DigitalOcean Ubuntu Droplet
- Agent: Ubuntu / Kali Linux
- Attack Type: Privilege Escalation

---

## 🧪 Test Performed

On the agent machine, the following command was executed:

```bash
sudo su