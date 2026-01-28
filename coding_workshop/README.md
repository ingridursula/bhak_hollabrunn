# Präsentations-Website für den Coding Workshop

## Überblick

Diese statische Website dient als interaktive Präsentation für deinen 4-stündigen Coding-Workshop. Sie enthält alle theoretischen Inhalte, die du während der ersten Stunde präsentieren möchtest.

## Struktur

Die Website besteht aus 4 HTML-Seiten und 1 CSS-Datei:

```
presentation/
├── index.html          - Startseite mit Überblick
├── grundlagen.html     - Was ist Coding, 3 Säulen, Begriffe
├── beispiele.html      - Code-Beispiele mit Erklärungen
├── ressourcen.html     - Tools, Dokumentationen, Lernplattformen
└── style.css           - Externes Stylesheet
```

## Verwendung

### Option 1: Direkt im Browser öffnen
1. Öffne `index.html` im Browser (Doppelklick oder Rechtsklick → Öffnen mit → Browser)
2. Navigation funktioniert über die Menüleiste

### Option 2: Mit Live Server (empfohlen für Präsentation)
1. Öffne den `presentation` Ordner in VS Code
2. Installiere die Extension "Live Server"
3. Rechtsklick auf `index.html` → "Open with Live Server"
4. Website öffnet sich automatisch und aktualisiert bei Änderungen

### Option 3: Online hosten
Du kannst den gesamten `presentation` Ordner auf Plattformen wie:
- GitHub Pages (kostenlos)
- Netlify (kostenlos)
- Vercel (kostenlos)

hochladen und den Link dann mit den Schülern teilen.

## Inhalte der einzelnen Seiten

### 1. index.html - Startseite
- Begrüßung und Motivation
- Überblick über den Workshop-Ablauf
- Was die Schüler lernen werden
- Timeline der 4 Unterrichtseinheiten

### 2. grundlagen.html - Grundlagen
- Was ist Coding? (mit anschaulichem Beispiel)
- Die 3 Säulen einer Website:
  - HTML (Struktur)
  - CSS (Design)
  - JavaScript (Verhalten)
- Wichtige Begriffe (Tag, Element, Attribut, etc.)
- Entwicklungsumgebung (Browser + Editor)

### 3. beispiele.html - Code-Beispiele
- Alle 8 Mini-Projekte erklärt
- Sortiert nach Schwierigkeitsgrad (Leicht, Mittel, Schwer)
- Was man in jedem Projekt lernt
- Code-Snippets
- Aufgaben zum Experimentieren
- Debugging-Tipps

### 4. ressourcen.html - Ressourcen
- Online-Editoren (CodePen, JSFiddle, Replit)
- Dokumentationen (W3Schools, MDN Web Docs)
- Lernplattformen (freeCodeCamp, Codecademy, Scrimba)
- YouTube-Kanäle (deutsch und englisch)
- Desktop-Editoren (VS Code, Sublime Text, etc.)
- Community-Ressourcen (Stack Overflow, Reddit)
- Nützliche Tools

## Design-Merkmale

Das Design ist bewusst schlicht und professionell gehalten:

- **Keine Icons im Text** - wie gewünscht
- **Klare Typografie** - System-Schriften für beste Lesbarkeit
- **Dezente Farbpalette** - Blau-Grau Töne
- **Responsive** - funktioniert auf allen Bildschirmgrößen
- **Gute Kontraste** - für Beamer-Präsentation optimiert
- **Sticky Navigation** - bleibt beim Scrollen sichtbar

## Farbschema

```css
Hauptfarben:
- Primär: #3498db (Blau)
- Text: #2c3e50 (Dunkelgrau)
- Hintergrund: #f5f5f5 (Hellgrau)
- Akzent: #667eea → #764ba2 (Gradient)

Semantische Farben:
- Leicht: #d4edda (Grün)
- Mittel: #fff3cd (Gelb)
- Schwer: #f8d7da (Rot)
```

## Anpassungen

Falls du etwas ändern möchtest, sind hier die wichtigsten Stellen:

### Farben ändern
In `style.css`:
- Zeile 167: Hero-Gradient
- Zeile 182: Link-Farbe
- Zeile 239: Timeline-Marker
- Zeile 357-372: Pillar-Farben (HTML=Rot, CSS=Blau, JS=Orange)

### Text ändern
Einfach die entsprechenden HTML-Dateien öffnen und editieren.

### Neue Seite hinzufügen
1. Neue HTML-Datei erstellen
2. Navigation kopieren von einer bestehenden Seite
3. `<link rel="stylesheet" href="style.css">` nicht vergessen!
4. In allen anderen Seiten den neuen Link zur Navigation hinzufügen

## Tipps für die Präsentation

### Vor dem Workshop:
1. Teste alle Links (ob sie funktionieren)
2. Öffne die Website auf dem Präsentations-Rechner
3. Zoome bei Bedarf mit Strg/Cmd + Plus
4. Prüfe, ob alles auf dem Beamer gut lesbar ist

### Während der Präsentation:
- Nutze die Navigation, um zwischen Themen zu wechseln
- Scrolle langsam, damit alle mitlesen können
- Bei Code-Beispielen: Erkläre Zeile für Zeile
- Zeige die Ressourcen-Seite am Ende
- Die Schüler können die URL später selbst öffnen

### Nach der ersten Stunde:
- Lass die Website auf dem Beamer offen
- Schüler können bei Fragen nachschauen
- Die Beispiele-Seite ist als Referenz hilfreich

## Offline-Nutzung

Die Website funktioniert komplett offline, da:
- Keine externen Bibliotheken geladen werden
- Alle Styles inline im CSS sind
- Keine externen Fonts verwendet werden
- Keine Bilder eingebunden sind

Das bedeutet: Du kannst den `presentation` Ordner auf einen USB-Stick kopieren und überall öffnen, auch ohne Internet!

## SEO und Meta-Tags

Falls du die Seite online stellst, könntest du noch hinzufügen:
```html
<meta name="description" content="Coding Workshop für Einsteiger">
<meta name="keywords" content="HTML, CSS, JavaScript, Tutorial">
```

## Browser-Kompatibilität

Die Website funktioniert in:
- Chrome/Edge (ab Version 90)
- Firefox (ab Version 88)
- Safari (ab Version 14)

Alle modernen Browser werden unterstützt.

## Lizenz

Du kannst diese Präsentation frei verwenden, anpassen und teilen.

---

## Schnellstart-Checklist

- [ ] Ordner `presentation` auf den Präsentations-Rechner kopieren
- [ ] `index.html` im Browser öffnen
- [ ] Navigation testen
- [ ] Schriftgröße auf Beamer prüfen (ggf. Browser-Zoom anpassen)
- [ ] URL notieren (falls online gehostet)
- [ ] Backup auf USB-Stick

Viel Erfolg mit deiner Präsentation!