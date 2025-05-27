# 🕷️ T-C (Test-Crawler)

T-C ist ein leichtgewichtiger, regelkonformer Test-Crawler zur Überprüfung von Webseiten auf Crawling-Erlaubnis.

## 🔍 Funktionen
- Liest `robots.txt`, Nutzungsbedingungen und AGB
- Sucht nach Crawlingverboten
- Ergebnis in `data.json` gespeichert
- Darstellung via `index.html` auf **GitHub Pages**
- Manuell auslösbar per GitHub Actions Workflow

## 🛠️ Nutzung

### ➤ 1. GitHub Pages aktivieren
- Gehe zu `Settings > Pages`
- Quelle: `main`, Ordner: `/ (root)`
- Ergebnis: `https://<dein-username>.github.io/T-C/`

### ➤ 2. Crawler manuell starten
- Gehe zu `Actions > Run Crawler`
- Klicke auf **"Run workflow"**
- Warte ~1 Minute – `data.json` wird aktualisiert & Seite zeigt neue Inhalte

## 🔒 Hinweis
Bitte beachte die robots.txt & Nutzungsbedingungen jeder Seite.  
**`Dieses Tool dient ausschließlich zu Test- und Forschungszwecken.`**
