# QG1o – Portfolio

Ein modernes, interaktives Portfolio – fokussiert auf klare UI, dezente Animationen und schnelle Ladezeiten.

## 🚀 Features

- 3-sektionales Layout: Profil, Fähigkeiten, Projekte, Kontakt
- Sanfte Scroll- und Hover-Effekte
- Responsives Design für Desktop und Mobile (Hamburger-Menü)
- Saubere Typografie mit Playfair Display und Source Sans Pro
- Einfache Struktur: reine HTML/CSS/JavaScript ohne Build-Setup

## 🛠️ Technologien

- Markup: HTML5
- Styling: CSS3 (Custom CSS, Media Queries)
- Interaktivität: Vanilla JavaScript (`script.js`)
- Assets: PNG/JPEG, Favicon

## 📦 Installation / Lokale Vorschau

Ohne Build-Tools sofort nutzbar. Optionen:

1) Direkt im Browser öffnen
- `index.html` im Dateiexplorer doppelklicken

2) Mit Live Server (empfohlen)
- In Cursor/VS Code: Rechtsklick auf `index.html` → „Open with Live Server“

3) Einfacher lokaler Server (Python)
```bash
python -m http.server 8000
# dann http://localhost:8000 im Browser öffnen
```

## 🧪 Struktur

- `index.html` – Seitenstruktur und Inhalte
- `style.css` – Layout, Farben, Typografie und Effekte
- `mediaqueries.css` – Responsive Breakpoints
- `script.js` – Hamburger-Menü und Interaktionen
- `assets/` – Bilder, Icons, PDF (Lebenslauf)
- `public/` – Favicon

## 🧭 Nutzung

- Links im Navigationsmenü springen zu Sektionen
- Projektkarten enthalten Buttons für GitHub und Live-Demos
- „Lebenslauf“-Button öffnet die PDF aus `assets/`

## 🖌️ Anpassung

- Farben: in `style.css` (z. B. Body-Hintergrund `#15508b`, Logo- und Titel-Farben)
- Schriften: Google Fonts (Playfair Display, Source Sans Pro)
- Links: in `index.html` die `onclick`-URLs der Buttons anpassen

## 🏗️ Build

Kein Build notwendig. Deployment z. B. via GitHub Pages:
- Repo auf GitHub pushen
- In den Repository-Einstellungen GitHub Pages für `main`/`root` aktivieren

## 📄 Lizenz

© 2026 QG1o. Alle Rechte vorbehalten.

## 🌐 Live Demo

[Portfolio Website](https://qg1o.github.io/portfolio1/)

## 📧 Kontakt

- GitHub: `QG1o`
- LinkedIn: `QG1o`
