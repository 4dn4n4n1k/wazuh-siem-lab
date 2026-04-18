# 🖥️ Command Monitoring Detection

## 📌 Objective
To test whether Wazuh can monitor and log command execution on a monitored endpoint.

---

## 🧱 Environment
- Wazuh Server: DigitalOcean Ubuntu Droplet
- Agent: Ubuntu / Kali Linux
- Monitoring Type: Command execution

---

## ⚙️ Configuration

The following configuration was added to the agent:

```xml
<localfile>
  <log_format>command</log_format>
  <command>whoami</command>
  <frequency>60</frequency>
</localfile>