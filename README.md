# Website Sidar Avci

Statische Website, gehostet über GitHub Pages.

## Struktur
| Datei / Ordner          | URL                        |
|-------------------------|----------------------------|
| `index.html`            | `/`                        |
| `arbeiten/index.html`   | `/arbeiten/`               |
| `impressum/index.html`  | `/impressum/`              |
| `datenschutz/index.html`| `/datenschutz/`            |
| `404.html`              | jede unbekannte Adresse    |
| `assets/img/`           | alle Bilder                |

## Neue Unterseite anlegen
Ordner mit kleinem, sprechendem Namen ohne Umlaute/Leerzeichen anlegen
(z. B. `leistungen/`), darin `index.html`. Ergebnis: `deinedomain.de/leistungen/`.
Intern immer mit Schrägstrich am Anfang und Ende verlinken: `href="/leistungen/"`.

## Livegang-Checkliste
- [ ] `noindex`-Zeile in allen HTML-Dateien entfernen
- [ ] `robots.txt` auf `Allow: /` umstellen
- [ ] `49NUMMER` durch echte WhatsApp-Nummer ersetzen
- [ ] Impressum + Datenschutz befüllen
- [ ] Freigabe FairWilly / Stockwerk einholen
- [ ] Alle `[VON SIDAR ERGÄNZEN]`-Stellen füllen
