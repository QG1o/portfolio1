# QG1o – Portfolio

Ein modernes, interaktives Portfolio – fokussiert auf klare UI, dezente Animationen und schnelle Ladezeiten.

## 🚀 Features

- 🌓 **Dark/Light Mode Toggle** – Vollständiger Theme-Switcher mit LocalStorage-Persistenz
- 📱 **Responsives Design** – Optimiert für Desktop, Tablet und Mobile (Hamburger-Menü)
- ✨ **Moderne UI** – Glassmorphism-Effekte, Gradient-Backgrounds und smooth Transitions
- 🎨 **CSS Variables System** – Vollständig anpassbare Themes über CSS-Variablen
- 📄 **4 Haupt-Sektionen** – Profil, Über mich, Fähigkeiten, Projekte, Kontakt
- 🎭 **Sanfte Animationen** – Hover-Effekte, Scroll-Behavior und cubic-bezier Transitions
- ♿ **Barrierefreiheit** – Semantisches HTML und ARIA-Labels
- ⚡ **Performance** – Sticky Navigation, optimierte Animationen, keine Dependencies

## 🛠️ Technologien

- **Markup**: HTML5 (semantisch, barrierefrei)
- **Styling**: CSS3 (CSS Variables, Flexbox, Glassmorphism, Animations)
- **Interaktivität**: Vanilla JavaScript (ES6+)
- **Storage**: LocalStorage API für Theme-Persistenz
- **Schriften**: Google Fonts (Playfair Display, Poppins)
- **Assets**: PNG/JPEG, Favicon

### Theme-System

Das Portfolio verfügt über ein vollständiges Dark/Light Mode System:

**🌙 Dark Mode (Standard)**
- Lila-violetter Gradient-Hintergrund (#667eea → #764ba2)
- Weiße Schrift mit hohem Kontrast
- Transparente Container mit Glassmorphismus-Effekt
- Invertierte Icons für optimale Sichtbarkeit

**☀️ Light Mode**
- Heller blau-grauer Gradient (#f0f4f8 → #d9e4f5)
- Dunkle Schrift für bessere Lesbarkeit
- Weiße Container mit subtilen Schatten
- Angepasste Icon-Filter

**💾 Persistenz**: Die Theme-Auswahl wird im LocalStorage gespeichert und beim nächsten Besuch automatisch geladen.

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

```
portfolio1/
│
├── index.html              # Haupt-HTML mit allen Sections
├── style.css               # Haupt-Stylesheet mit Theme-System
├── mediaqueries.css        # Responsive Design Styles
├── script.js               # Theme-Toggle & Hamburger-Menü
│
├── assets/                 # Bilder und Icons
│   ├── profile-pic.jpeg
│   ├── about-pic.jpeg
│   ├── github.png
│   ├── linkedin.png
│   ├── email.png
│   ├── checkmark.png
│   ├── experience.png
│   ├── education.png
│   ├── arrow.png
│   ├── project11.png
│   ├── project22.png
│   ├── project33.png
│   └── resume-example.pdf
│
├── public/                 # Favicon
│   └── favicon.ico
│
└── README.md               # Diese Dokumentation
```

## 🧭 Nutzung

- **Navigation**: Links im Menü springen smooth zu den jeweiligen Sektionen
- **Theme-Toggle**: Button rechts unten (🌙/☀️) wechselt zwischen Dark/Light Mode
- **Projekte**: Projektkarten enthalten Buttons für GitHub-Repos und Live-Demos
- **Lebenslauf**: Button öffnet die PDF aus `assets/resume-example.pdf`
- **Social Links**: Direkte Verlinkungen zu LinkedIn und GitHub
- **Mobile**: Hamburger-Menü für kleine Bildschirme

## 🖌️ Anpassung

### Theme-Farben ändern

Die Theme-Farben können einfach über CSS-Variablen in `style.css` angepasst werden:

```css
:root {
    /* Dark Mode Farben */
    --bg-gradient-start: #667eea;
    --bg-gradient-end: #764ba2;
    --accent-color: #f39c12;
    --text-primary: rgba(255, 255, 255, 0.95);
    /* ... weitere Variablen */
}

body.light-mode {
    /* Light Mode Farben */
    --bg-gradient-start: #f0f4f8;
    --bg-gradient-end: #d9e4f5;
    /* ... */
}
```

### Eigene Inhalte einfügen

- **Bilder**: Ersetze die Bilder im `assets/` Ordner
- **Texte**: Aktualisiere die Inhalte in `index.html`
- **Social Links**: Passe die URLs in den `onclick`-Attributen an
- **Projekte**: Füge neue Projekt-Container in der Projekte-Section hinzu
- **Schriften**: Google Fonts (Playfair Display, Poppins) in `style.css` ändern

## 🏗️ Build & Deployment

Kein Build notwendig. Deployment z. B. via GitHub Pages:
- Repo auf GitHub pushen
- In den Repository-Einstellungen GitHub Pages für `main`/`root` aktivieren
- Alternativ: Netlify, Vercel, oder jeden statischen Hosting-Service

## 🌐 Browser-Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

## ⚡ Performance-Features

- CSS-Transitions mit `cubic-bezier` für smooth Animationen
- Sticky Navigation für bessere User Experience
- Optimierte Filter und `backdrop-blur`-Effekte
- LocalStorage für Theme-Präferenz (kein Flackern beim Reload)
- Keine externen Dependencies oder Frameworks
- Schnelle Ladezeiten durch optimierte Assets

## 📄 Lizenz

© 2026 QG1o. Alle Rechte vorbehalten.

## 🌐 Live Demo

[Portfolio Website](https://qg1o.github.io/portfolio1/)

## 📧 Kontakt

- GitHub: `QG1o`
- LinkedIn: `QG1o`
