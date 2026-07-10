# Green Bowl Baunatal — Website

Moderne, animierte **Multi-Page-Website** für **Green Bowl**, das Poke-Bowl-,
Salat- und Smoothie-Restaurant in der Glaspassage am Marktplatz 3 in Baunatal.

## Highlights

- **Design:** Frisches Grün-/Weiß-Farbschema (Organic-Biophilic-Stil)
- **Animationen:** Scroll-Reveal, animierte Zähler, schwebende Elemente,
  Parallax im Hero, Hover-Effekte, Scroll-Fortschrittsbalken
- **Mehrere Seiten** mit gemeinsamem Header/Footer und aktivem Menü-Zustand
- **Responsive** für Mobil, Tablet und Desktop
- **Zugänglich:** WCAG-orientierte Kontraste, `prefers-reduced-motion`-Support,
  funktioniert auch ohne JavaScript

## Seiten

| Datei | Inhalt |
|-------|--------|
| `index.html`      | Startseite: Hero, Vorteile, beliebte Bowls, Bowl-Baukasten, Über-uns- & Galerie-Teaser |
| `speisekarte.html`| Volle Speisekarte (Signature Bowls, Vegan & Veggie, Smoothies & Extras) + Bowl-Baukasten |
| `ueber-uns.html`  | Geschichte, Werte und Zahlen zum Restaurant |
| `galerie.html`    | Bildergalerie mit Hover-Effekten |
| `kontakt.html`    | Adresse, Öffnungszeiten, Karte und Kontaktformular |
| `impressum.html`  | Impressum (Pflichtangaben nach § 5 DDG) – Platzhalter ausfüllen |
| `datenschutz.html`| Datenschutzerklärung (DSGVO) inkl. Hinweise zu Google Fonts, OpenStreetMap & Unsplash |

> **Rechtlicher Hinweis:** `impressum.html` und `datenschutz.html` sind Vorlagen mit
> `[…]`-Platzhaltern. Bitte mit den echten Unternehmensdaten füllen und im Zweifel
> rechtlich prüfen lassen, bevor die Seite online geht.

## Struktur

```
index.html · speisekarte.html · ueber-uns.html · galerie.html · kontakt.html
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
