
https://ipstyle.github.io/
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="img/banner-dark.svg">
  <img src="img/banner-light.svg" alt="ipstyle — native apps for Mac and iPhone">
</picture>

<p align="right"><sub><a href="README.de.md">Deutsch →</a></sub></p>

Two apps on the Mac App Store, two more on the way. No Electron, no trackers, no accounts — what can run locally, runs locally.

<table>
<tr>
<td width="50%" valign="top">
<img src="img/icon-aicockpit.png" width="56" alt="">
<br><b>AI-Cockpit</b><br>
Every AI budget in one place.
<br><br>
<img src="img/card-aicockpit.png" width="100%" alt="AI-Cockpit: usage tiles for Claude, ChatGPT and the OpenAI API with sparklines and forecasts">
<br><br>
<a href="https://apps.apple.com/app/id6802014255"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-dark.svg">
<img src="img/mas-badge-light.svg" alt="Download AI-Cockpit on the Mac App Store" width="156">
</picture></a>
<br>
<sub>CHF 3.50 once · macOS 14+<br><a href="https://aicockpit.info">aicockpit.info</a> · <a href="https://github.com/ipstyle/ai-cockpit-docs">Docs</a></sub>
</td>
<td width="50%" valign="top">
<img src="img/icon-barbox.png" width="56" alt="">
<br><b>BarBox</b><br>
The menu bar, tidied up.
<br><br>
<img src="img/card-barbox.png" width="100%" alt="BarBox: live CPU, memory and GPU stats, status chips and favourite tools">
<br><br>
<a href="https://apps.apple.com/app/id6802093315"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-dark.svg">
<img src="img/mas-badge-light.svg" alt="Download BarBox on the Mac App Store" width="156">
</picture></a>
<br>
<sub>Free · macOS 14+ · GPL-3.0<br><a href="https://github.com/ipstyle/barbox">Source</a> · <a href="https://ipstyle.github.io/barbox/">Website</a></sub>
</td>
</tr>
</table>

**AI-Cockpit** tracks Claude, ChatGPT/Codex, the OpenAI and Anthropic APIs and Kimi in one window — plus the Claude Code sessions running on your Mac, with subagents, token shares and context windows.
**BarBox** puts CPU, memory and GPU live in the menu bar, next to image compression, text from image, PDF merging, timers, weather and rates.

### Next up

<table>
<tr>
<td width="50%" valign="top">
<img src="img/soon-baumaengel.svg" width="100%" alt="Baumängel Tracker: rooms with open defects, progress per room, and a PDF report">
<br>
<b>Baumängel Tracker</b> · <a href="https://github.com/ipstyle/baumaengel-tracker">source</a><br>
<sub>Snag lists for iPhone — rooms, defects, photos, deadlines, and a clean PDF at handover. <b>In App Review.</b> MIT.</sub>
</td>
<td width="50%" valign="top">
<img src="img/soon-fristwart.svg" width="100%" alt="Fristwart: counts back from a cancellation deadline to the day the letter has to be sent">
<br>
<b>Fristwart</b> · <a href="https://ipstyle.github.io/fristwart-web/">about</a><br>
<sub>Never miss a cancellation deadline — it counts back to the day you actually have to send. <b>In development.</b></sub>
</td>
</tr>
</table>

### How I build

Both Mac apps ship through the Mac App Store, fully sandboxed. BarBox is GPL-3.0 — build it yourself with `swift build -c release` if you'd rather.

Nothing leaves your device. Credentials, where any are needed, live in the macOS Keychain and never in a settings file. No analytics, no accounts, no ads. Every app speaks English and German.

AI-Cockpit was reviewed against OWASP ASVS 4.0, OWASP MASVS, the Apple Secure Coding Guide, RFC 8252/7636 and the CWE Top 25.

### More

**[ipstyle.github.io](https://ipstyle.github.io)** — all four apps on one page, with full screenshots and the reasoning behind them.

### Found a bug?

Open an issue in the relevant repo. Please report security issues through the repo's private reporting feature rather than as a public issue.
