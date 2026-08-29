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

Monitor Buddy started with a very simple problem: switching between a PC, PS5, and other devices on one monitor without constantly reaching for the monitor's physical controls.

We wanted a simple software solution. Our monitor did not provide the feature we needed, and we did not want to solve the problem by buying expensive hardware just to make input switching easier.

### 🔎 Finding the starting point

While searching for a solution, we found the YouTube video **“Tech Tip: Switch Monitor Input with a Keyboard Shortcut.”** It introduced us to **ControlMyMonitor (CMM)**, DDC/CI commands, and the idea that monitor functions could be controlled from Windows with keyboard shortcuts.

That gave us the starting point. Then came the question:

> **“What if we took those things to the next level?”**

### 🧪 From experiments to a proper application

The first versions were experiments. We moved between **PowerShell, Python, and C#**, testing different ways to communicate with the monitor and make the idea actually work.

One of the early PowerShell-based versions worked, but it was not the release experience we wanted. Some security tools also flagged the early script-based approach, which made one thing very clear: **making the feature work was only the beginning.**

We wanted something better:

**A proper Windows application. A portable build. A simple experience. And a release that people could download with confidence.**

So we kept rebuilding and testing. We connected pieces, broke things, investigated what went wrong, fixed them, and tested again.

Eventually, the project became what we wanted it to be: **Monitor Buddy as an actual application**, rather than just a collection of scripts and experiments.

### 🙏 Thank you to ControlMyMonitor

A very special thank-you goes to **ControlMyMonitor and its creator, Nir Sofer / NirSoft**.

ControlMyMonitor gave us an important technical foundation for the project. Instead of having to build the entire monitor-control layer from scratch, we could experiment with real DDC/CI monitor controls and command-line operations. That made it possible for us to explore the idea, learn what was possible, and gradually build Monitor Buddy around the problem we were trying to solve.

We also genuinely respect the fact that ControlMyMonitor is provided as freeware. The official ControlMyMonitor license allows free distribution as long as the utility is not charged for, sold, or distributed as part of a commercial product, and requires the distributed files to be included without modification. citeturn0search0

Because Monitor Buddy currently uses the **ControlMyMonitor executable**, we chose to keep Monitor Buddy **free and publicly available** rather than turn the project into a paid product built around a dependency whose license does not permit commercial distribution.

That decision felt right to us.

> **If a project can put so much work into making a powerful tool available for free, why shouldn't we do the same with what we build on top of it?**

CMM gave us a foundation to experiment with. Monitor Buddy is our independent application built around our own user experience, configuration, monitor identification, profiles, shortcuts, startup behavior, and other project-specific work.

We are grateful for the work that made our experiment possible. ❤️

### 🚀 The build we finally wanted to share

The current application is designed around the original goal: make monitor input switching easier without forcing people to buy additional hardware.

The public **v1.1.0 Actual App** release is portable — there is no traditional installer. Extract the ZIP, run the application, and use it.

It also includes the things we learned were important during development, including monitor identification, DDC/CI control, startup support, and a straightforward user experience.

And after all the early experiments, we checked the final public release with VirusTotal. The release ZIP received **0 / 64 detections** at the time of analysis.

That result matters to us because this project did not start as a polished application. It started as a problem, an experiment, and a lot of trial and error — including early versions that were not suitable for a public release — and eventually became something we were comfortable putting in public.

### ❤️ Why release it?

Once it worked for our setup, we asked a second question:

> **“Why keep it just for ourselves?”**

Other people have one-screen setups, PCs and consoles, and hardware they cannot or do not want to replace. If Monitor Buddy can save someone else from repeatedly reaching behind their monitor, then the project is worth sharing.

So we decided to make Monitor Buddy free and available publicly, with optional community support in the future if people want to help development continue.

The development process was simple in theory:

**Build → test → break → investigate → fix → test again.**

And yes, there was an AI sitting next to us confidently suggesting things that sometimes broke the exact thing we had just fixed. 😂

But that's part of the story too.

### 🎯 From a flagged experiment to a release we could stand behind

One of the most important parts of this journey was realizing that a working prototype is not automatically a good public product.

The early script-based approach helped prove the idea, but security warnings showed us that we needed to take the next step. We did not want people downloading Monitor Buddy and immediately wondering why their security software was complaining about the way it was built.

So we rebuilt, tested, simplified the distribution, and moved toward a proper application.

The result is **Monitor Buddy v1.1.0 — Actual App**: a portable Windows release that can be extracted and launched without a traditional installer.

Before publishing, we also scanned the release ZIP with VirusTotal. At the time of analysis, it received **0 / 64 detections**.

That does not mean any software can be guaranteed universally safe forever, but it was an important checkpoint for us: **we finally had a release we felt comfortable putting in front of other people.**

### 🙏 Where the idea started

A special thank-you to the creator of **“Tech Tip: Switch Monitor Input with a Keyboard Shortcut.”** The video helped us discover ControlMyMonitor and the command-based approach that gave us a direction to explore.

The video gave us a starting point. **Monitor Buddy is our own independent implementation and project.**

**Original inspiration video:** https://www.youtube.com/watch?v=ue2dijq7wdM

### 🔗 Independent project

Monitor Buddy is an independent CStrikerDJ project. The development, testing, design, maintenance, and decisions behind Monitor Buddy are our own.

ControlMyMonitor / NirSoft, the inspiration video, and other third-party tools or projects mentioned here are credited for their respective contributions or technical reference. They are **not affiliated with, responsible for, or associated with the development of Monitor Buddy.**

## 🔒 Privacy

Monitor Buddy is a local Windows utility. It does not require an online account for normal operation.

## 📄 License

See [LICENSE](LICENSE).

---

**Monitor Buddy**  
Universal monitor input control for Windows.

**Built because we needed it. Shared because someone else might need it too.**
