
# MasscanGUI – Interface for Masscan

[![GitHub stars](https://img.shields.io/github/stars/mehdirzfx/MasscanGUI?style=for-the-badge&logo=github&color=yellow)](https://github.com/mehdirzfx/MasscanGUI/stargazers)

<img width="982" height="672" alt="image" src="https://github.com/user-attachments/assets/5e70a59d-68cc-4966-919a-8aef6f01aacf" />

> 📖 [Read this document in Persian (فارسی)](README.fa.md)

## Introduction

**MasscanGUI** is a professional graphical user interface for the famous **Masscan** port scanner. It provides all Masscan features and parameters in a simple, user-friendly environment. No need to download Masscan separately – the executable is included alongside the GUI in the release package.

## Key Features

- ✅ **Full support for all Masscan parameters** (basic & advanced)
- 🌍 **Country‑based scanning** (IP ranges for 18 countries + custom ranges)
- 📝 **Multiple output formats** including `IP:PORT`, JSON, XML, Grepable, etc.
- 🚀 **Real‑time output display** while scanning
- ⚙️ **Network adapter settings** (adapter, IP, MAC, VLAN, source port)
- 📄 **Save & resume scans** + rotating output files
- 🔍 **Read binary scan files** and convert to text formats
- 🧩 **Sharding support** for distributed scans
- 🖥️ **No command line required** – everything is clickable
- ⚡ **Intelligent rate adjustment** – automatic speed optimization based on network conditions
- 📡 **WinPcap/Npcap library support** for optimal Windows performance

## How to Use

1. Place `MasscanGUI.exe` and `masscan.exe` in the same folder.
2. Run the application.
3. In the **Scan** tab, enter the IP range or target address.
4. Select ports (presets available).
5. Optionally adjust advanced settings (rate, retries, sharding, etc.).
6. Click **Start Scan** and watch results appear in the **Results** tab.

> **Note:** The masscan executable is included in the release – no separate installation or download is required.

## Country‑Based Scanning

- Go to the **Countries** tab.
- Select a country – its IP ranges will be displayed.
- You can also enter custom ranges in the text box below.
- Click **Scan This Country** to start scanning.

## IP:PORT Output

In the **Output** tab, choose the `IP:PORT` format. The output will look like:

```
192.168.1.1:80
192.168.1.5:443
```

## Requirements

- Windows (7, 8, 10, 11) – also runs on Linux/macOS with Python 3 if using the source.
- No Python installation needed (standalone .exe provided)
- **WinPcap** or **Npcap** (for optimal scanning performance)

## Download

Download the executable (along with masscan.exe) from the **[Releases](https://github.com/mehdirzfx/MasscanGUI/releases)** section.

## GitHub Repository

[https://github.com/mehdirzfx/MasscanGUI](https://github.com/mehdirzfx/MasscanGUI)

## Author

**Mehdizfx (s3nat0r)**

## ⭐️ Support This Project

If you find this project useful, please consider giving it a **star** on GitHub.  
Your support helps increase visibility and encourages further development.

[![GitHub stars](https://img.shields.io/github/stars/mehdirzfx/MasscanGUI?style=for-the-badge&logo=github&color=yellow)](https://github.com/mehdirzfx/MasscanGUI/stargazers)

## فایل دوم: `README.fa.md` (فارسی)

```markdown
