# 🚀 AWS Toolkit

<p align="center">
  <img src="https://img.shields.io/badge/version-3.0-orange?style=flat">
  <img src="https://img.shields.io/badge/platform-Amazon%20Connect-232F3E?logo=amazonaws&logoColor=white">
  <img src="https://img.shields.io/badge/engine-Tampermonkey-00485B?style=flat">
  <img src="https://img.shields.io/badge/language-JavaScript%20ES6%2B-f7df1e?logo=javascript&logoColor=black">
</p>

> A productivity toolkit for **Amazon Connect user administration** — bulk user
> management, one-click routing profile automation, and agent selection
> utilities, packed into a lightweight Tampermonkey userscript.

## 📸 Preview

<p align="center"><img src="https://github.com/Mkhimer69/AWS-Toolkit/blob/main/screenshots/aws-toolkit-v3.png?raw=true" width="800" alt="AWS Toolkit v3"></p>

## 📥 Installation

**1. Install [Tampermonkey](https://www.tampermonkey.net/)**

📺 [Video guide](screenshots/install-tampermonkey.mp4)

**2. Install AWS Toolkit** — open the script link, Tampermonkey detects it automatically:

```
https://raw.githubusercontent.com/Mkhimer69/AWS-Toolkit/main/AWS-Toolkit.user.js
```

📺 [Install demo](screenshots/install%20AWS%20toolkit.gif)

**3. Click Install** → **4. Refresh Amazon Connect** — the toolkit loads automatically.

🔄 **Auto-updates**: Tampermonkey checks for new versions and offers one-click updates whenever a new version is published.

## ✨ Features

### 👥 User Management
- 📥 Add user emails directly from clipboard
- 📋 View stored user list
- ✅ / ❌ Bulk select & deselect users
- 🧹 Clear stored users

### 🔀 Routing Profile Automation
One-click profile application:

| | | | |
|---|---|---|---|
| Driver Chat Focus | Driver Default Omnichannel | Driver Email Focus | Driver Voice Focus |

### 🎨 User Experience
- Modern floating, draggable panel
- 💾 Remembers last selected routing profile
- 🔔 Visual status notifications & desktop notifications for long operations
- ⚡ Lightweight and fast

## 🎥 Demo Videos

| Video | What it shows |
|---|---|
| [Install Tampermonkey](screenshots/install-tampermonkey.mp4) | Extension setup from scratch |
| [AWS Toolkit Demo](screenshots/aws-toolkit-demo.mp4) | Core workflows in action |
| [Live Bridge Demo](screenshots/live-bridge-demo.mp4) | v3 Live Bridge between pages |

## 🆕 What's New in v3.0

| Feature | What it does |
|---|---|
| ⚡ **Live Bridge System** | Real-time bridge between the Connect Analytics Dashboard and User Administration pages — seamless data sharing |
| 🎲 **Random Agent Injection** | Pick a routing profile → inject N randomly selected agents into the user stash for bulk actions |
| 📡 **Analytics Sync** | Agent data syncs between AWS pages automatically — no exports, imports, or copy-paste |
| 📊 **Progress Tracking** | Visual progress bars & live status for bulk selection tasks |
| 🔔 **Desktop Notifications** | Browser notifications when long-running operations finish |
| 🚀 **Performance** | Optimized bulk select/deselect for large user lists |
| 🎨 **UI Enhancements** | Better status indicators, sync timestamps, improved Live Bridge Picker |

## 📌 Use Cases

Agent onboarding · routing profile changes · bulk user administration ·
operations workflow optimization · contact center administration

## ⚙️ Requirements

- [Tampermonkey](https://www.tampermonkey.net/) browser extension
- Amazon Connect account with **user administration permissions**
- Works on `*.my.connect.aws` / `*.awsapps.com`

## 🛠 Technology

JavaScript (ES6+) · Tampermonkey · DOM Automation · Browser Storage (localStorage) · Amazon Connect UI Automation

## ⚠ Disclaimer

This project was created for productivity and workflow automation purposes.
Always test changes in accordance with your organization's policies and
change-management procedures.

---

<div align="center">
<b>🚀 AWS Toolkit</b><br><i>Bulk admin work, one click at a time.</i><br><br>
**Fathy Mkhimer** · Lead Real-Time Analyst · [GitHub](https://github.com/Mkhimer69)
</div>
