# Hi, I'm Albert (ipstyle) 👋

Indie developer from Switzerland 🇨🇭 — I build native macOS tools.

## 🧠 AI-Cockpit — all your AI limits at a glance

A macOS menu bar app that keeps every AI budget you have in one place:
**Claude** subscription usage, **ChatGPT/Codex** quotas, **OpenAI** and
**Anthropic** API costs, **Kimi** credit — plus the **Claude Code sessions**
currently running on your Mac, with token shares and context windows.

<a href="https://aicockpit.info"><img src="img/dashboard.jpg" alt="AI-Cockpit dashboard" width="720"></a>

**→ [aicockpit.info](https://aicockpit.info)** · Mac App Store: coming soon ·
[Documentation](https://github.com/ipstyle/ai-cockpit-docs)

Security-reviewed against OWASP ASVS 4.0, OWASP MASVS, the Apple Secure
Coding Guide, RFC 8252/7636 and the CWE Top 25. English and German interface.

## 🧰 Toolbox

**[Toolbox](https://github.com/ipstyle/toolbox)** — free, open-source macOS
menu bar toolbox: desktops, app list, image resizing, text from image, PDF
merging, QR codes, timers, passwords, network, Time Machine, currency rates
and SARON. SwiftUI, DE/EN.

## How I build

Everything runs locally. Session contents are never transmitted; credentials
live in the macOS Keychain, not in a settings file. AI-Cockpit is Developer-ID
signed and notarized. Toolbox is open source — build it yourself with
`swift build -c release`.

## Found a bug?

Open an issue — for AI-Cockpit in
[ai-cockpit-docs](https://github.com/ipstyle/ai-cockpit-docs/issues), for
Toolbox in [its repo](https://github.com/ipstyle/toolbox/issues). Please
report security issues via the repo's private reporting feature, not as a
public issue.
