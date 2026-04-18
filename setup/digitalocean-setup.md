# ☁️ DigitalOcean Droplet Setup

## 📌 Objective
To create a cloud server for deploying the Wazuh SIEM platform.

---

## 🧱 Droplet Configuration

- Provider: DigitalOcean
- OS: Ubuntu 22.04 LTS
- Plan: Basic
- RAM: 4 GB (minimum)
- Storage: 50 GB SSD
- Authentication: SSH Key

---

## 🌐 Networking Configuration

Firewall rules were configured to allow the following ports:

| Port | Purpose |
|------|--------|
| 22   | SSH access |
| 443  | Wazuh Dashboard |
| 1514 | Agent communication |
| 1515 | Agent enrollment |

---

## 🔐 Initial Access

Connected to the server using:

```bash
ssh root@your_droplet_ip