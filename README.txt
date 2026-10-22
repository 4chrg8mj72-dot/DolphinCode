Dolphin Code Beta 3 – FTP-Paket
================================

Dateien:
- index.html          → Hauptseite (als Startseite hochladen)
- logo.png            → Logo
- icon-192.png        → PWA-Icon 192×192
- icon-512.png        → PWA-Icon 512×512
- apple-touch-icon.png→ Apple-Touch-Icon
- manifest.json       → Web-App-Manifest
- sw.js               → Service Worker (Offline-Unterstützung)

Upload-Anleitung:
1. Alle Dateien aus diesem Ordner in denselben Ordner auf dem FTP-Server laden
   (z. B. in den Webroot oder in einen Unterordner).
2. Sicherstellen, dass index.html die Startdatei ist
   (oder die Domain darauf zeigt).
3. HTTPS ist erforderlich, damit „Zum Startbildschirm hinzufügen“
   und der Service Worker zuverlässig funktionieren.

Nach dem Upload:
- Seite im Browser öffnen
- Button „Zur Startseite hinzufügen“ (gelb) verwenden
  oder über das Browser-Menü installieren.

Version: Beta 3
