<picture>
  <source media="(prefers-color-scheme: dark)" srcset="img/banner-de-dark.svg">
  <img src="img/banner-de-light.svg" alt="ipstyle — native Apps für Mac und iPhone">
</picture>

<p align="right"><sub><a href="README.md">English →</a></sub></p>

Native Apps für Mac und iPhone. Kein Electron, keine Tracker, keine Konten — was lokal laufen kann, läuft lokal.

<table>
<tr>
<td width="50%" valign="top">
<img src="img/icon-aicockpit.png" width="60" alt="">
<h3>AI-Cockpit</h3>
<p>Alle KI-Budgets an einem Ort — Claude, ChatGPT/Codex, OpenAI- und Anthropic-API, Kimi — dazu die Claude-Code-Sessions, die gerade auf dem Mac laufen, mit Subagenten, Token-Anteilen und Kontextfenstern.</p>
<img src="img/menubar-aicockpit.jpg" width="100%" alt="AI-Cockpit in der Menüleiste">
<p>
<a href="https://apps.apple.com/app/id6802014255"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-de-dark.svg">
<img src="img/mas-badge-de-light.svg" alt="AI-Cockpit im Mac App Store laden" height="40">
</picture></a>
</p>
<sub>CHF 3.50, einmalig · macOS 14+ · <a href="https://aicockpit.info">aicockpit.info</a> · <a href="https://github.com/ipstyle/ai-cockpit-docs">Doku</a></sub>
</td>
<td width="50%" valign="top">
<img src="img/icon-barbox.png" width="60" alt="">
<h3>BarBox</h3>
<p>Die Menüleiste, aufgeräumt — CPU, Arbeitsspeicher und GPU live, Bilder verkleinern, Text aus Bild, PDFs zusammenfügen, Timer, Wetter und Kurse. Alles einen Klick entfernt.</p>
<img src="img/menubar-barbox.jpg" width="100%" alt="BarBox in der Menüleiste">
<p>
<a href="https://apps.apple.com/app/id6802093315"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-de-dark.svg">
<img src="img/mas-badge-de-light.svg" alt="BarBox im Mac App Store laden" height="40">
</picture></a>
</p>
<sub>Gratis · macOS 14+ · GPL-3.0 · <a href="https://github.com/ipstyle/barbox">Quellcode</a> · <a href="https://ipstyle.github.io/barbox/">Website</a></sub>
</td>
</tr>
</table>

<details>
<summary><b>Richtig anschauen</b> — die vollen Oberflächen</summary>
<br>
<img src="img/dashboard.jpg" width="600" alt="AI-Cockpit: Anbieter nebeneinander, Sparklines, Prognosen, Kostenaufschlüsselung">
<br><br>
<img src="img/barbox.jpg" width="300" alt="BarBox: Stats, Status-Chips, Regler, Favoriten, Werkzeuge und Wetter">
</details>

### In Arbeit

**[Baumängel Tracker](https://github.com/ipstyle/baumaengel-tracker)** — Mängelprotokoll mit Fotodokumentation fürs iPhone: Räume, Mängel, Fristen und am Schluss ein sauberes PDF. Im App-Review. MIT.

**Fristwart** — keine Kündigungsfrist mehr verpassen; rechnet zurück bis zum Tag, an dem abgeschickt sein muss. In Entwicklung.

### Wie ich baue

Beide Mac-Apps kommen über den Mac App Store, vollständig sandboxed. BarBox steht unter GPL-3.0 — wer lieber selbst baut, nimmt `swift build -c release`.

Nichts verlässt das Gerät. Zugangsdaten, wo überhaupt welche nötig sind, liegen im Schlüsselbund und nie in einer Einstellungsdatei. Keine Analyse, keine Konten, keine Werbung.

AI-Cockpit wurde gegen OWASP ASVS 4.0, OWASP MASVS, den Apple Secure Coding Guide, RFC 8252/7636 und die CWE Top 25 geprüft.

### Fehler gefunden?

Issue im betreffenden Repo aufmachen. Sicherheitsprobleme bitte über die private Meldefunktion des Repos statt als öffentliches Issue.
