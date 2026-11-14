# Hau das Erdmännchen!

Ein rosa Hau-drauf-Spiel fürs Handy (optimiert fürs iPhone 17 Pro).

**Spielen:** `index.html` im Browser öffnen, am besten über GitHub Pages.

**Als App aufs iPhone:** Link in Safari öffnen → „Teilen“ → „Zum Home-Bildschirm“. Das Spiel bekommt ein eigenes Erdmännchen-Icon, startet im Vollbild und funktioniert nach dem ersten Öffnen auch offline. Das Icon und der Offline-Modus brauchen eine echte Webadresse (z. B. GitHub Pages), beim direkten Öffnen der Datei funktionieren sie nicht.

## So geht's
1. **40 Sekunden hauen** – 9 Löcher, die Erdmännchen kommen immer schneller.
   - Erdmännchen: +10 · Goldenes Erdmännchen: +50 · Kaktus: −20 (nicht hauen!)
   - Treffer in Folge geben einen Combo-Multiplikator (×2 ab 5, ×3 ab 10, ×4 ab 15). Danebenhauen oder eins entwischen lassen setzt ihn zurück.
2. **Level 2 – Nacht in der Kalahari** (35 Sekunden, bis zu 4 Löcher gleichzeitig offen)
   - Helm-Erdmännchen: 2× hauen, +25 · Zeit-Erdmännchen: +3 Sekunden · Schlange: −30 (Finger weg!)
   - Wer Level 2 einmal erreicht hat, kann es im Startbildschirm direkt anwählen.
3. **Die Erdmännchen-Königin** – danach taucht die Königin mit Krone auf. 10 Treffer in 15 Sekunden besiegen sie (+250 Bonus). Kakteen versuchen dich abzulenken.
4. **Erdmännchen-Party** – alle 9 Erdmännchen tanzen mit Partyhüten, es regnet Konfetti, und du bekommst deinen Rang (vom „Sandkorn-Anfänger“ bis zur „Legende der Kalahari“). Tipp die Tänzer an, dann machen sie einen Salto.

Rekord wird lokal gespeichert. Wechselt man die App, pausiert das Spiel automatisch.

## Dateien
- `index.html` – das komplette Spiel
- `manifest.webmanifest` – Name, Farben und Icon für den Home-Bildschirm
- `sw.js` – Offline-Speicher (lädt immer zuerst die neueste Version)
- `icons/` – App-Icon als SVG und PNG (180, 192, 512 px)
