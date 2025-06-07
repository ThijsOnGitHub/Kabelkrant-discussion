# Alle velden uitgelegd

Op de website gebruiken we velden van *Advanced Custom Fields* (ACF). Hieronder leggen we uit wat ze doen en hoe ze met elkaar samenhangen.

## Hoe hoort alles bij elkaar?

1. **Berichten** krijgen een **categorie**. Die categorie bepaalt automatisch de achtergrond en het icoon op de dia.
2. Met **dia's** stel je een programma samen. Een dia kan berichten uit een of meer categorieën tonen, maar je kunt ook losse afbeeldingen of tekst gebruiken.
3. Een **tv‑zender** bestaat uit een reeks dia's. Zo bepaal je wat er op het scherm te zien is.

## Velden bij een bericht
- **show_on_tv** – zet het bericht aan of uit voor de kabelkrant.
- **tv_settings.title** – titel op de dia.
- **tv_settings.text** – tekst op de dia.
- **tv_settings.length** – aantal seconden dat de dia blijft staan.
- **tv_settings.category** – kies de categorie waar dit bericht bij hoort.
- **tv_settings.image** – één afbeelding voor het bericht.
- **tv_settings.images** – meerdere afbeeldingen voor een diavoorstelling.
- **tv_settings.imageLength** – tijd per afbeelding in seconden.
- **tv_settings.titleOnlyFirstImage** – toon de titel alleen bij de eerste afbeelding.
- **tv_settings.end_date** – na deze datum verdwijnt het bericht.

## Velden bij een categorie
- **display_name** – naam die onderin de dia verschijnt.
- **tv_background** – standaardachtergrond voor alle berichten in deze categorie.
- **icon** – het icoon dat bij de categorie hoort.
- **end_date_offset** – verlengt automatisch de einddatum van berichten.

## Velden bij een dia
- **type** – kies `postblock` (laat berichten zien), `image` of `textSlide`.
- **postblock.category** – uit welke categorie(en) de berichten komen.
- **postblock.standardLength** – standaardduur van elke dia.
- **postblock.standardImageLength** – standaardduur van afbeeldingen.
- **postblock.mixSlides** – combineer berichten uit meerdere categorieën.
- **image.images** – afbeeldingen om te tonen.
- **image.length** – duur van een afbeelding.
- **image.text** – tekst bij de afbeelding.
- **image.textOnlyFirstImage** – toon de tekst alleen bij de eerste afbeelding.
- **textSlide.title** – titel van de tekstdia.
- **textSlide.text** – de tekst zelf.
- **textSlide.backgroundImage** – achtergrond voor de tekstdia.
- **textSlide.length** – duur van de dia.
- **textSlide.showCategory** – laat onderaan een blokje met het icoon en de tekst van een categorie zien.
- **textSlide.category.icon** – icoon in dat blokje.
- **textSlide.category.text** – tekst in dat blokje.
- **fromDate** en **toDate** – periode waarin de dia getoond wordt.
- **hasTimespan** – bepaalt of de dia op vaste dagen/uren verschijnt.
- **timespan.days** – dagen waarop de dia zichtbaar is.
- **timespan.hours** – uren waarop de dia zichtbaar is.
- **tv-channel** – op welke tv-zender deze dia staat.

## Velden bij een tv-zender
- **kabelkrant_logo** – logo voor de zender.
- **kabelkrant_title_bar** – afbeelding voor de bovenbalk.
- **kabelkrant_accent_color** – accentkleur van de zender.
- **kabelkrant_dia** – de dia's die bij deze zender horen.
