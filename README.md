# 🖥️ PC Clean-up AEAL

A computer cleaner that helps **schools** and **companies** easily maintain Windows PCs.  
Removes bloatware, resets desktop clutter, restores default wallpapers, runs health-checks, manages Wi-Fi profiles, and automates system cleanup — all with a friendly UI and role-based PIN access.

![screenshot](docs/screenshot-placeholder.png)

---

## ✨ Features

- 🔒 **PIN-based access**  
  - Operator (**4589**) – Basic cleanup and Wi-Fi tasks  
  - Technician (**1256**) – Full access to advanced tools, logs and revert options  

- 🧹 **System Cleanup**  
  - Removes non-essential Windows apps (bloatware)  
  - Clears temp files, cache, and Recycle Bin  
  - Resets desktop icons (keeps Edge and Recycle Bin only)  
  - Restores default Windows wallpaper  

- 📶 **Wi-Fi Management**  
  - Auto-connects to predefined SSID with stored password  
  - Skips gracefully if no network is available  

- 🩺 **Health Checker**  
  - Runs system diagnostics before tasks  
  - Shows overall status (OK/Warn/Fail) with details  

- 📊 **Logs & Reports**  
  - Saves logs in `C:\ProgramData\AfonsoQueiroz\PC-Cleaner\logs`  
  - Collects manufacturer, model, and serial for inventory  

- ↩️ **Revert Option**  
  - Roll back the last cleanup if needed  

---

## 🚀 Getting Started

### Prerequisites
- Windows 10 or 11 (recommended)  
- [Node.js](https://nodejs.org/) v16+ (for development/build)  
- [npm](https://www.npmjs.com/)  

### Development
```bash
git clone https://github.com/<your-org>/<your-repo>.git
cd <your-repo>
npm install
npm run start
