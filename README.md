<picture>
  <source media="(prefers-color-scheme: dark)" srcset="img/banner-dark.svg">
  <img src="img/banner-light.svg" alt="ipstyle — native apps for Mac and iPhone">
</picture>

<p align="right"><sub><a href="README.de.md">Deutsch →</a></sub></p>

Native apps for Mac and iPhone. No Electron, no trackers, no accounts — what can run locally, runs locally.

<table>
<tr>
<td width="50%" valign="top">
<img src="img/icon-aicockpit.png" width="60" alt="">
<h3>AI-Cockpit</h3>
<p>Every AI budget in one place — Claude, ChatGPT/Codex, OpenAI and Anthropic API, Kimi — plus the Claude Code sessions running on your Mac, with subagents, token shares and context windows.</p>
<img src="img/menubar-aicockpit.jpg" width="100%" alt="AI-Cockpit in the menu bar">
<p>
<a href="https://apps.apple.com/app/id6802014255"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-dark.svg">
<img src="img/mas-badge-light.svg" alt="Download AI-Cockpit on the Mac App Store" height="40">
</picture></a>
</p>
<sub>CHF 3.50, one-time · macOS 14+ · <a href="https://aicockpit.info">aicockpit.info</a> · <a href="https://github.com/ipstyle/ai-cockpit-docs">Docs</a></sub>
</td>
<td width="50%" valign="top">
<img src="img/icon-barbox.png" width="60" alt="">
<h3>BarBox</h3>
<p>The menu bar, tidied up — live CPU, memory and GPU stats, image compression, text from image, PDF merging, timers, weather and finance. Everything one click away.</p>
<img src="img/menubar-barbox.jpg" width="100%" alt="BarBox in the menu bar">
<p>
<a href="https://apps.apple.com/app/id6802093315"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-dark.svg">
<img src="img/mas-badge-light.svg" alt="Download BarBox on the Mac App Store" height="40">
</picture></a>
</p>
<sub>Free · macOS 14+ · GPL-3.0 · <a href="https://github.com/ipstyle/barbox">Source</a> · <a href="https://ipstyle.github.io/barbox/">Website</a></sub>
</td>
</tr>
</table>

<details>
<summary><b>See them properly</b> — full dashboards</summary>
<br>
<img src="img/dashboard.jpg" width="600" alt="AI-Cockpit dashboard: providers side by side, sparklines, forecasts, cost breakdown">
<br><br>
<img src="img/barbox.jpg" width="300" alt="BarBox dashboard: stats, status chips, sliders, favorites, tools and weather">
</details>

### In the works

**[Baumängel Tracker](https://github.com/ipstyle/baumaengel-tracker)** — snag lists with photo documentation for iPhone: rooms, defects, deadlines, and a clean PDF report at the end. In App Review. MIT.

**Fristwart** — never miss a cancellation deadline; it counts back to the day you have to send. In development.

### How I build

Both Mac apps ship through the Mac App Store, fully sandboxed. BarBox is GPL-3.0 — build it yourself with `swift build -c release` if you'd rather.

Nothing leaves your device. Credentials, where any are needed, live in the macOS Keychain and never in a settings file. No analytics, no accounts, no ads.

AI-Cockpit was reviewed against OWASP ASVS 4.0, OWASP MASVS, the Apple Secure Coding Guide, RFC 8252/7636 and the CWE Top 25.

### Found a bug?

Open an issue in the relevant repo. Please report security issues through the repo's private reporting feature rather than as a public issue.
