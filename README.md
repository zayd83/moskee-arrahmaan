# Moskee Arrahmaan Dordrecht — website

Statische website (HTML/CSS/JS). Geen build-stap nodig: open `index.html` of upload
de map naar elke webhost.

## Structuur
```
index.html          Homepage
over-ons.html        Over ons
steun-ons.html       Steun ons (contributie, incasso, donatie)
activiteiten.html    Activiteiten + fotogalerij + WhatsApp
onderwijs.html       Koranonderwijs
contact.html         Contactgegevens + kaart
css/style.css        Gedeelde stylesheet (design tokens bovenaan)
js/main.js           Mobiel menu + jaartal
images/              Foto's (personen zijn geblurd)
```

## Nog in te vullen (placeholders)
1. **Gebedstijden** — in `index.html`, bij het blok met `class="prayer__card"`,
   staat een comment met de Mawaqit-iframe. Vervang de placeholder-slots door de
   iframe en vul jullie Mawaqit-ID in.
2. **Donatie/betaallinks** — knoppen met `href="#"` in `steun-ons.html`
   (betaallink, automatische incasso, eenmalig doneren) koppelen aan de juiste URL's.
3. **WhatsApp Community** — knop in `activiteiten.html` en `onderwijs.html`
   koppelen aan de uitnodigingslink.
4. **Social media** — nog niet toegevoegd aan de footer; links aanleveren dan zet ik
   ze erbij.

## Foto's / privacy
- Alle herkenbare personen op de foto's zijn geblurd (conform de vraag), inclusief
  `images/activiteiten-5.jpg` (zwembad), die inmiddels ook op `activiteiten.html` staat.

## Kleuren (in css/style.css → :root)
Brand-groen `#4A5B56` · brand-groen donker `#3A4844` · taupe-accent `#B2AFA0` (alleen op donkere vlakken of als rand/vulling) · warme off-white `#F4F2EC` · tekst `#242A27`.
