# Webdesign-Agentur – Onepager Website (Grundstruktur)
# Webdesign-Agentur – Onepager Website

Dieses Projekt beschreibt eine **einfach gehaltene, aber saubere Basis-Website** für eine fiktive Webdesign-Agentur.  
Die Seite soll als Ausgangspunkt dienen und später um zusätzliche Funktionen erweitert werden.
Eine moderne, statische Onepager-Startseite für eine fiktive Webdesign-Agentur. Die Seite liefert einen schnellen Überblick über Leistungen, Referenzen, Prozessablauf und eine Kontaktmöglichkeit – optimiert für Desktop und mobile Geräte.

> **Wichtig:** Verwende **Platzhalter** anstelle von echten Namen, z.B. `AGENTUR_NAME`, `KUNDEN_NAME`, `STADT_NAME`, `info@agentur-domain.tld`.
> **Hinweis:** Bitte weiterhin Platzhalter wie `AGENTUR_NAME`, `KUNDEN_NAME`, `STADT_NAME` oder `info@agentur-domain.tld` verwenden und später mit echten Angaben ersetzen.

---

## Ziel des Projekts

Erstelle eine **moderne, responsive Onepager-Website** mit folgenden Eigenschaften:

- Darstellung einer Webdesign-Agentur (`AGENTUR_NAME`)
- Klare Struktur, die sich später leicht erweitern lässt
- Sauberes, gut kommentiertes HTML, CSS und JavaScript
- Fokus auf **Lesbarkeit** und **Erweiterbarkeit**

---
## Features
- Strukturierte Abschnitte: Hero, Leistungen, Referenzen/Portfolio, Prozess, Call-to-Action und Kontaktformular.
- Responsives Layout mit Flex/Grid, Karten-Design und vertikaler Prozess-Timeline.
- Mobiles Navigationsmenü mit Hamburger-Button sowie Smooth Scrolling zu Ankern.
- Klar getrennte Assets-Struktur für Icons und Bilder.

## Technischer Stack
- **HTML5** für die Seitenstruktur (`index.html`).
- **CSS3** mit Flexbox/Grid in `css/styles.css` für Layout, Typografie und Komponenten-Styling.
- **Vanilla JavaScript** in `js/main.js` für Menü-Toggle und sanftes Scrollen.
- Keine Build-Tools oder Frameworks nötig.

Verwende für die erste Version nur **Basis-Webtechnologien**:

- **HTML5** für die Struktur
- **CSS3** (gern mit Flexbox/Grid) für Layout & Styling  
  - Optional: Eine einzelne globale CSS-Datei (`styles.css`)
- **Vanilla JavaScript** (optional, minimal) für kleine Interaktionen  
  - z.B. Smooth Scrolling oder mobiles Menü

Keine Frameworks (React, Vue, usw.) in der Grundversion.

---

## Dateistruktur

Erstelle eine einfache Projektstruktur:

## Projektstruktur
```text
root/
├─ index.html
├─ css/
│  └─ styles.css
├─ js/
│  └─ main.js
└─ assets/
   ├─ img/
   └─ icons/
   ├─ img/      # Platzhalter für Bilder
   └─ icons/    # Platzhalter für Icons
```

## Nutzung
1. Repository klonen oder herunterladen.
2. Öffne `index.html` direkt im Browser oder starte einen lokalen Server (z. B. via VS Code "Live Server").
3. Scrolle durch die Abschnitte oder nutze die Navigation; auf mobilen Geräten lässt sich das Menü über den Hamburger-Button öffnen/schließen.

## Anpassung
- Inhalte anpassen: Ersetze Platzhaltertexte in `index.html` durch echte Agentur- und Kundendaten.
- Bilder/Icons ergänzen: Lege Assets in `assets/img` bzw. `assets/icons` ab und aktualisiere die Verweise.
- Farben/Typografie ändern: Passe Variablen und Styles in `css/styles.css` an.

## Weiterentwicklung
- Formular-Handling erweitern (z. B. Backend-Anbindung oder Form-Service).
- Weitere Unterseiten oder Blog/Case-Study-Seiten hinzufügen.
- Performance-Optimierungen (Bildkomprimierung, Caching-Strategien) einplanen.
