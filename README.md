# 🚀 GREAT SHIFAT FF BAN TOOL
### PREMIUM EDITION • v2.2 (OB55)

Welcome to the **GREAT SHIFAT FF BAN TOOL**. This is a powerful, Python-based Command Line Interface (CLI) tool designed to manage Free Fire accounts efficiently. 

> **⚠️ DISCLAIMER:** This tool is created for educational purposes only. The developer (**GREAT SHIFAT**) is not responsible for any misuse, account bans, or damages caused by this tool. Use it at your own risk.

---

## ✨ Features
- **📂 Ban from File:** Input a `.txt` or `.json` file containing `uid:password` to ban multiple accounts at once.
- **🔑 Ban Direct Token:** Input a JWT (`ey...`) or Access Token directly to ban a specific account.
- **📝 Auto Logging:** Automatically saves successful and failed attempts into `.txt` log files.
- **🎨 Premium UI:** Beautiful terminal interface with colors, animations, and ASCII art.

---

## 🛠️ Requirements
- **Termux** (Android) or any Linux-based terminal.
- **Python 3.x**
- Required Python Libraries: `requests`, `pycryptodome`, `protobuf`, `urllib3`

---

## 📥 Installation & Usage (Termux)

Follow these simple steps to install and run the tool on your Android device:

### Step 1: Update Packages & Install Requirements
Open Termux and run the following commands:
```bash
pkg update && pkg upgrade -y
pkg install python git -y
pip install requests pycryptodome protobuf urllib3
