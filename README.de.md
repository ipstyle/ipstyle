<picture>
  <source media="(prefers-color-scheme: dark)" srcset="img/banner-de-dark.svg">
  <img src="img/banner-de-light.svg" alt="ipstyle — native Apps für Mac und iPhone">
</picture>

<p align="right"><sub><a href="README.md">English →</a></sub></p>

Zwei Apps im Mac App Store, zwei weitere unterwegs. Kein Electron, keine Tracker, keine Konten — was lokal laufen kann, läuft lokal.

<table>
<tr>
<td width="50%" valign="top">
<img src="img/icon-aicockpit.png" width="56" alt="">
<br><b>AI-Cockpit</b><br>
Alle KI-Budgets an einem Ort.
<br><br>
<img src="img/card-aicockpit.png" width="100%" alt="AI-Cockpit: Verbrauchskacheln für Claude, ChatGPT und die OpenAI-API mit Sparklines und Prognosen">
<br><br>
<a href="https://apps.apple.com/app/id6802014255"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-de-dark.svg">
<img src="img/mas-badge-de-light.svg" alt="AI-Cockpit im Mac App Store laden" width="156">
</picture></a>
<br>
<sub>CHF 3.50 einmalig · macOS 14+<br><a href="https://aicockpit.info">aicockpit.info</a> · <a href="https://github.com/ipstyle/ai-cockpit-docs">Doku</a></sub>
</td>
<td width="50%" valign="top">
<img src="img/icon-barbox.png" width="56" alt="">
<br><b>BarBox</b><br>
Die Menüleiste, aufgeräumt.
<br><br>
<img src="img/card-barbox.png" width="100%" alt="BarBox: CPU, Arbeitsspeicher und GPU live, Status-Chips und Lieblingswerkzeuge">
<br><br>
<a href="https://apps.apple.com/app/id6802093315"><picture>
<source media="(prefers-color-scheme: dark)" srcset="img/mas-badge-de-dark.svg">
<img src="img/mas-badge-de-light.svg" alt="BarBox im Mac App Store laden" width="156">
</picture></a>
<br>
<sub>Gratis · macOS 14+ · GPL-3.0<br><a href="https://github.com/ipstyle/barbox">Quellcode</a> · <a href="https://ipstyle.github.io/barbox/">Website</a></sub>
</td>
</tr>
</table>

**AI-Cockpit** führt Claude, ChatGPT/Codex, die OpenAI- und Anthropic-API und Kimi in einem Fenster zusammen — dazu die Claude-Code-Sessions, die gerade auf dem Mac laufen, mit Subagenten, Token-Anteilen und Kontextfenstern.
**BarBox** bringt CPU, Arbeitsspeicher und GPU live in die Menüleiste, daneben Bilder verkleinern, Text aus Bild, PDFs zusammenfügen, Timer, Wetter und Kurse.

### Als Nächstes

<table>
<tr>
<td width="50%" valign="top">
<img src="img/soon-baumaengel-de.svg" width="100%" alt="Baumängel Tracker: Räume mit offenen Mängeln, Fortschritt je Raum und PDF-Protokoll">
<br>
<b>Baumängel Tracker</b> · <a href="https://github.com/ipstyle/baumaengel-tracker">Quellcode</a><br>
<sub>Mängelprotokoll fürs iPhone — Räume, Mängel, Fotos, Fristen und zur Übergabe ein sauberes PDF. <b>Im App-Review.</b> MIT.</sub>
</td>
<td width="50%" valign="top">
<img src="img/soon-fristwart-de.svg" width="100%" alt="Fristwart: rechnet von der Kündigungsfrist zurück auf den Tag, an dem der Brief raus muss">
<br>
<b>Fristwart</b> · <a href="https://ipstyle.github.io/fristwart-web/">worum es geht</a><br>
<sub>Keine Kündigungsfrist mehr verpassen — rechnet zurück bis zum Tag, an dem wirklich abgeschickt sein muss. <b>In Entwicklung.</b></sub>
</td>
</tr>
</table>

### Wie ich baue

Beide Mac-Apps kommen über den Mac App Store, vollständig sandboxed. BarBox steht unter GPL-3.0 — wer lieber selbst baut, nimmt `swift build -c release`.

Nichts verlässt das Gerät. Zugangsdaten, wo überhaupt welche nötig sind, liegen im Schlüsselbund und nie in einer Einstellungsdatei. Keine Analyse, keine Konten, keine Werbung. Jede App spricht Deutsch und Englisch.

AI-Cockpit wurde gegen OWASP ASVS 4.0, OWASP MASVS, den Apple Secure Coding Guide, RFC 8252/7636 und die CWE Top 25 geprüft.

### Fehler gefunden?

Issue im betreffenden Repo aufmachen. Sicherheitsprobleme bitte über die private Meldefunktion des Repos statt als öffentliches Issue.
