# Unser Kalender

Eine mobile, romantische Kalender-Website für zwei Menschen – mit Heute-,
Kalender-, Momente- und Wir-Ansicht sowie sechs persönlichen Erinnerungsfotos.

## GitHub-Pages-Version

Die veröffentlichte Version läuft vollständig im Browser. Termine,
Statusmeldungen und Namen werden nur im lokalen Speicher des jeweiligen Geräts
gesichert. Ein ICS-Export überträgt einen Schnappschuss in Apple Kalender,
Google Kalender oder Samsung Kalender.

GitHub Pages stellt kein Backend bereit. Darum synchronisiert diese Variante
Einträge nicht live zwischen zwei Geräten. Der vollständige Quellcode enthält
zusätzlich eine Cloudflare-D1-API für eine spätere Live-Bereitstellung.

## Entwicklung

Benötigt Node.js `>=22.13.0`.

```bash
npm install
npm run dev
npm run build:pages
npm test
```

Der statische GitHub-Pages-Build wird in `pages-dist/` erzeugt.
