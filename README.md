# Website Sidar Avci

Statische Website, gehostet über GitHub Pages.

## Struktur
| Datei / Ordner          | URL                        |
|-------------------------|----------------------------|
| `index.html`            | `/`                        |
| `arbeiten/index.html`   | `/arbeiten/`               |
| `referenzen/index.html` | `/referenzen/`             |
| `arbeiten/av-vertrags-bot/index.html` | `/arbeiten/av-vertrags-bot/` (Case Study) |
| `arbeiten/nomo/index.html` | `/arbeiten/nomo/` (Case Study) |
| `arbeiten/ems-loccum/index.html` | `/arbeiten/ems-loccum/` (Case Study) |
| `arbeiten/stroeer/index.html` | `/arbeiten/stroeer/` (Case Study, Video per YouTube erst nach Klick) |
| `impressum/index.html`  | `/impressum/`              |
| `datenschutz/index.html`| `/datenschutz/`            |
| `404.html`              | jede unbekannte Adresse    |
| `assets/img/`           | alle Bilder                |
| `assets/img/referenzen/dreamberry/` | Beiträge Dreamberry (`t/` 480 px, `l/` 1080 px) |

## Neue Unterseite anlegen
Ordner mit kleinem, sprechendem Namen ohne Umlaute/Leerzeichen anlegen
(z. B. `leistungen/`), darin `index.html`. Ergebnis: `deinedomain.de/leistungen/`.
Intern immer mit Schrägstrich am Anfang und Ende verlinken: `href="/leistungen/"`.

## Livegang (25.10.2026)
- [x] Startseite von `/vorschau/` nach `/` übernommen, `/vorschau/` leitet auf `/` weiter
- [x] `/arbeiten/` leitet auf `/#arbeiten` weiter (Übersichtsseite gibt es nicht)
- [x] Alle Links `/vorschau/` → `/`, `noindex` entfernt (außer 404 und Weiterleitungen)
- [x] `robots.txt` erlaubt alles, `sitemap.xml` angelegt, Canonical- und Linkvorschau-Tags (`og.png`) auf allen Seiten
- [x] Hero-Fotos und Schrift als Dateien statt Base64
- [x] Impressum und Datenschutz befüllt, Freigaben liegen vor
- [ ] USt-IdNr. ins Impressum, sobald vorhanden
- [ ] GitHub → Settings → Pages: „Enforce HTTPS“ an
- [ ] Google Search Console: Domain bestätigen, `sitemap.xml` einreichen
