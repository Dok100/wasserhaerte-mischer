# 💧 Wasserhärte-Mischer

Eine kleine interaktive Web-App, um die **Gesamthärte von Wasser** zu berechnen und Mischungen aus Leitungswasser und Mineralwasser zu simulieren.  
Die App läuft vollständig im Browser (auch offline) und speichert Eingaben lokal auf dem Gerät.

---

## ✨ Funktionen
- Berechnung der **Wasserhärte aus Calcium- und Magnesiumwerten** (°dH).
- Zwei getrennte Härte-Rechner:
  - Leitungswasser
  - Mineralwasser
- Übernahme der berechneten Härten direkt in den Mischrechner.
- Mischrechner:
  - Zielhärte bestimmen
  - Gesamtmenge oder feste Menge Leitungswasser vorgeben
  - Berechnung der benötigten Mengen von LW und MW
- Optional: **Preisangaben** für Kostenberechnung.
- **Lokale Speicherung** aller Eingaben im Browser (localStorage).
- Optimiert für Desktop 💻 und iPhone/iPad 📱.

---

## 🚀 Nutzung
1. Öffne die Seite direkt über GitHub Pages:  
   👉 [https://dok100.github.io/wasserhaerte-mischer/](https://dok100.github.io/wasserhaerte-mischer/)

2. Auf dem iPhone/iPad:  
   - In Safari öffnen → Teilen → „Zum Home-Bildschirm“  
   - Die App erscheint wie eine normale App mit eigenem Icon.

---

## ⚙️ Installation (lokal)
Falls du die App lokal auf deinem Rechner öffnen willst:
1. Datei `index.html` herunterladen.
2. Doppelklick → öffnet sich im Standardbrowser.
3. Fertig ✅

Oder über einen kleinen lokalen Server:
```bash
python3 -m http.server 8000
```
→ Dann im Browser `http://localhost:8000` aufrufen.

---

## 🖼 Icon
Das App-Icon (`icon.png`) ist im Repository enthalten und wird automatisch als Homescreen-Icon auf iOS angezeigt.  
Falls du es ändern möchtest, tausche die Datei aus und achte darauf, dass der `<link rel="apple-touch-icon" href="icon.png">` im `index.html` gesetzt ist.

---

## 📜 Lizenz
Dieses Projekt ist privat für den persönlichen Gebrauch gedacht.  
Eine kommerzielle Nutzung ist nicht vorgesehen.
