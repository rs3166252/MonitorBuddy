# Monitor Buddy

**Universal monitor input switching for Windows.**

Monitor Buddy lets you switch compatible monitor inputs with configurable keyboard shortcuts using DDC/CI.

## 🚀 Get Monitor Buddy

**[Download the latest release](https://github.com/rs3166252/MonitorBuddy/releases)**

Visit the official website for the product overview, compatibility information, setup guidance, and the full project story:

**https://monitorbuddy.cstrikerdj.in**

## ✨ What it does

- DDC/CI-based monitor input switching
- Per-monitor profiles
- Configurable input names and keyboard shortcuts
- Multiple connected monitors can have their own profiles
- Refresh and scan controls for monitor/input discovery
- System-tray operation
- Portable operation with setup assistance
- Automatic ControlMyMonitor dependency setup with manual EXE/ZIP fallback

## 🖥️ Requirements & compatibility

- Windows
- A monitor that exposes the required DDC/CI controls
- A display connection that allows DDC/CI communication

Compatibility depends on the monitor, firmware, connection path, GPU/driver behavior, and the DDC/CI capabilities exposed by the display.

**DDC/CI support does not guarantee that every function, including input switching, is available.**

Monitor Buddy is designed to be dynamic and portable. When users report compatibility problems, we investigate and patch issues where the problem can be addressed by the application. Some limitations may ultimately come from the monitor's own DDC/CI implementation.

## 🎥 How to use

The official YouTube walkthrough will be linked here when published.

For setup questions and practical help, use the YouTube comments or join the Discord community.

## 💬 Community & support

**Discord:** https://discord.cstrikerdj.in

**YouTube:** Official tutorial link coming soon.

**GitHub Issues:** Use Issues for reproducible bugs and technical problems.

## 🛡️ Security

The **Monitor Buddy v1.1.0** release ZIP was scanned with VirusTotal.

**Result: 0 / 64 security vendors detected the file as malicious at the time of analysis.**

**SHA-256:**

`8cfab64e6480f855f83a78f480902a9d2b9f030c6606b47297ee3ba5d3dfae34`

**[View VirusTotal Scan Results](https://www.virustotal.com/gui/file/8cfab64e6480f855f83a78f480902a9d2b9f030c6606b47297ee3ba5d3dfae34/detection)**

## 🐛 Report a bug

Found a reproducible problem? Please open a **GitHub Issue** and include:

- Windows version
- Monitor model
- Connection type
- What you expected to happen
- What actually happened
- Steps to reproduce
- Any useful error information or screenshots

General questions and setup help are better suited to Discord or YouTube comments.

## 📋 Releases & changelog

- **[Latest releases](https://github.com/rs3166252/MonitorBuddy/releases)** — download published Windows builds
- **[Changelog](CHANGELOG.md)** — see what changed between releases

## ❤️ The story behind Monitor Buddy

Monitor Buddy started with a problem we were actually struggling with: switching between a PC, PS5, and other devices on one monitor without constantly reaching for the monitor controls.

We searched for a solution, but our monitor did not provide the feature we needed and we did not want to solve the problem by buying expensive hardware.

During that search we found the YouTube video **“Tech Tip: Switch Monitor Input with a Keyboard Shortcut.”** The video introduced us to **ControlMyMonitor**, commands, and the idea of using keyboard shortcuts to control monitor functions.

Then came the question:

> **“What if we took those things to the next level?”**

We started building our own solution. The early experiments moved through Python, C#, and PowerShell. We connected pieces, tested them, broke things, fixed them, and kept going until Monitor Buddy became a real application that worked for our setup.

Once it worked, we asked a second question:

> **“Why keep it just for ourselves?”**

Other people have one-screen setups, PCs and consoles, and hardware they cannot or do not want to replace. So we decided to make Monitor Buddy free, with optional community support in the future if people want to help development continue.

The development process was simple in theory:

**Build → test → break → investigate → fix → test again.**

And yes, there was an AI sitting next to us confidently suggesting things that sometimes broke the exact thing we had just fixed. 😂

### 🙏 Where the idea started

A special thank-you to the creator of **“Tech Tip: Switch Monitor Input with a Keyboard Shortcut.”** The video helped us discover ControlMyMonitor and the command-based approach that gave us a direction to explore.

The video gave us a starting point. **Monitor Buddy is our own independent implementation and project.**

**Original inspiration video:** https://www.youtube.com/watch?v=ue2dijq7wdM

### 🔗 Independent project

Monitor Buddy is an independent CStrikerDJ project. The development, testing, design, maintenance, and decisions behind Monitor Buddy are our own.

People, videos, tools, and projects mentioned here are credited for inspiration or technical reference where applicable. They are **not affiliated with, responsible for, or associated with the development of Monitor Buddy.**

## 🔒 Privacy

Monitor Buddy is a local Windows utility. It does not require an online account for normal operation.

## 📄 License

See [LICENSE](LICENSE).

---

**Monitor Buddy**  
Universal monitor input control for Windows.

**Built because we needed it. Shared because someone else might need it too.**
