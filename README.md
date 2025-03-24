# E-Spektiv Hole Updates

Dieses Repository enthält Updates für das E-Spektiv Hole System.

## Repository-Struktur

- `latest.json`: Enthält Informationen zur neuesten Version
- `releases/`: Verzeichnis mit allen Versionen
  - `1.0.0/`: Verzeichnis für Version 1.0.0
    - `full.zip`: Vollständige Installationsdatei
    - `checksums.md5`: MD5-Prüfsummen für die Dateien
    - `checksums.sha256`: SHA256-Prüfsummen für die Dateien

## Update-Prozess

Das E-Spektiv Hole System prüft automatisch auf Updates in diesem Repository. Wenn eine neue Version verfügbar ist, wird der Benutzer darüber informiert und kann das Update herunterladen und installieren.

## Versionschronik

### Version 1.0.0 (2025-03-24)

- Erste offizielle Version
- Automatische Ignorierung vorhandener Einschusslöcher beim Aktivieren der Erkennung
- Integration von bis zu 5 unabhängigen ROIs
- PDF-Berichtsgenerierung mit detaillierten Trefferinformationen
- Perspektivkorrektur zur Bildentzerrung
- Dark Mode und andere Anpassungsmöglichkeiten
- Vollständige Progressive Web App (PWA) Unterstützung