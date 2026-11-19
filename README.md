# 🛠️ IT-Support Desk (100 % kostenlos & Open Source)

Ticketsystem für den IT-Support mit Videositzung/Bildschirmfreigabe (Jitsi) und Fernsteuerung (RustDesk). Läuft im Browser, ohne Build und ohne Backend. Kein AnyDesk, keine Lizenzkosten.

## Funktionen
- Tickets anlegen, bearbeiten, löschen (Status, Priorität, Kategorie, Zuweisung), Suche, Filter, Dashboard
- Notizverlauf pro Ticket
- Jitsi-Videositzung pro Ticket (Bildschirmfreigabe) + Kunden-Link
- RustDesk-ID speichern und Fernsteuerung per Klick starten
- Export/Import als JSON, Dunkelmodus

## Installation
1. `index.html` ins GitHub-Repo, unter Settings → Pages den Branch `main` aktivieren.
2. Oder lokal `index.html` im Browser öffnen.

## Komplett kostenlos betreiben
| Teil | Kostenlose Lösung |
|---|---|
| Ticketsystem | diese App (GitHub Pages ist gratis) |
| Video/Bildschirm | `meet.jit.si` (gratis, Einbettung zeitlich begrenzt) oder eigener Jitsi-Server: https://github.com/jitsi/docker-jitsi-meet |
| Fernsteuerung | RustDesk (https://rustdesk.com) - Client gratis; optional eigener Server mit `docker-compose.yml` |

Eigene Jitsi-Domain unter *Einstellungen* eintragen. Der Kunde installiert RustDesk und nennt dir seine ID + Einmalpasswort.

## Hinweise
- Daten liegen im `localStorage` des Browsers: regelmäßig exportieren.
- Mehrere Techniker brauchen ein Backend (Roadmap: Node + SQLite).

Lizenz: MIT
