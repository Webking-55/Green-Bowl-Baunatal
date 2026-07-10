# Green Bowl Baunatal — Website

Moderne, animierte One-Page-Website für **Green Bowl**, das Poke-Bowl-,
Salat- und Smoothie-Restaurant in der Glaspassage am Marktplatz 3 in Baunatal.

## Highlights

- **Design:** Frisches Grün-/Weiß-Farbschema (Organic-Biophilic-Stil)
- **Animationen:** Scroll-Reveal, animierte Zähler, schwebende Elemente,
  Parallax im Hero, Hover-Effekte, Scroll-Fortschrittsbalken
- **Sektionen:** Hero, Vorteile, Bowls-Menü, „Bowl selbst zusammenstellen“,
  Über uns, Galerie, Call-to-Action, Kontakt & Öffnungszeiten mit Karte
- **Responsive** für Mobil, Tablet und Desktop
- **Zugänglich:** WCAG-orientierte Kontraste, `prefers-reduced-motion`-Support,
  funktioniert auch ohne JavaScript

## Struktur

```
index.html            # Seiteninhalt
assets/css/styles.css # Styles & Animationen
assets/js/main.js     # Scroll-Reveal, Zähler, Mobile-Menü, Parallax
```

## Lokal ansehen

Einfach `index.html` im Browser öffnen – oder ein kleiner lokaler Server:

```bash
python3 -m http.server 8000
# dann http://localhost:8000 aufrufen
```

## Hinweise

- Die Produktfotos werden über [Unsplash](https://unsplash.com) eingebunden
  (Platzhalter). Für den Live-Betrieb am besten durch echte Fotos der eigenen
  Bowls ersetzen (`assets/img/` anlegen und die `src`-Pfade in `index.html`
  anpassen).
- Menü, Preise und Öffnungszeiten bitte final mit dem aktuellen Angebot abgleichen.
