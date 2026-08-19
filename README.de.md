<picture>
  <source media="(prefers-color-scheme: dark)" srcset="img/banner-de-dark.svg">
  <img src="img/banner-de-light.svg" alt="ipstyle — native Apps für Mac und iPhone">
</picture>

<p align="center"><a href="https://ipstyle.github.io"><b>ipstyle.github.io →</b></a></p>
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

<p align="center">
<picture><source media="(prefers-color-scheme: dark)" srcset="img/trust-sandboxed-de-dark.svg"><img src="img/trust-sandboxed-de-light.svg" alt="Mac App Store — Sandboxed" width="255"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/trust-noanalytics-de-dark.svg"><img src="img/trust-noanalytics-de-light.svg" alt="Keine Analyse · Konten · Werbung" width="283"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/trust-asvs-de-dark.svg"><img src="img/trust-asvs-de-light.svg" alt="OWASP ASVS 4.0 · MASVS" width="246"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/trust-apple-de-dark.svg"><img src="img/trust-apple-de-light.svg" alt="Apple Secure Coding Guide" width="244"></picture>
<picture><source media="(prefers-color-scheme: dark)" srcset="img/trust-rfc-de-dark.svg"><img src="img/trust-rfc-de-light.svg" alt="RFC 8252/7636 · CWE Top 25" width="266"></picture>
</p>

**Ruhend gespeichert.** API-Schlüssel und Anmeldungen liegen ausschliesslich im macOS-Schlüsselbund — vom Betriebssystem verschlüsselt, an dieses Gerät gebunden, nie mit iCloud synchronisiert. Nichts Sensibles landet in einer Einstellungsdatei, einer Datenbank oder einem Log.

**Auf dem Weg.** Jede Verbindung läuft über HTTPS zu einer festen, veröffentlichten Liste von Servern — sonst nichts, Weiterleitungen werden nie befolgt. Beide Apps nennen jeden Server namentlich in ihren Datenschutzhinweisen — selbst nachlesen statt einer Zusammenfassung glauben.

**Bleibt deins.** Der Nutzungsverlauf lässt sich jederzeit als HTML oder CSV exportieren und genauso leicht in den Einstellungen löschen. Nichts liegt hinter einem Login, den nur ich kontrolliere — es ist deine Datei. BarBox steht unter GPL-3.0, du musst mir also nichts davon glauben: der Netzwerkcode ist öffentlich, `swift build -c release` baut ihn selbst.

Jede App spricht Deutsch und Englisch.

### Mehr

**[ipstyle.github.io](https://ipstyle.github.io)** — alle vier Apps auf einer Seite, mit vollen Screenshots und dem Warum dahinter.

### Fehler gefunden?

Issue im betreffenden Repo aufmachen. Sicherheitsprobleme bitte über die private Meldefunktion des Repos statt als öffentliches Issue.
