---
title: Links
draft: false
tags:
  - markdown
description: Uitleg over het toevoegen van links naar websites en andere bestanden.
date: 2024-01-01
aliases:
  - andere bestanden
difficulty: 1
---
In Markdown kunnen links worden toegevoegd door gebruik te maken van de volgende syntax:

```
Ga naar [Google](https://www.google.com) en zoek op "katten", klik vervolgens rechts op de oranje knop naast de afbeeldingen.
```

Resultaat:

Ga naar [Google](https://www.google.com) en zoek op "katten", klik vervolgens rechts op de oranje knop naast de afbeeldingen.
## Bestanden binnen de wiki

Naast het linken naar externe websites, kunnen binnen Obsidian ook andere bestanden worden gelinkt. Dit wordt gedaan door de bestandsnaam gevolgd door een pipe (`|`) en de gewilde tekst toe te voegen binnen 2 sets blokhaakjes (`[]`) zoals in dit voorbeeld:

```
Andere bestanden kunnen ook gelinkt worden, bijvoorbeeld de [[index|homepagina]]!
```

Resultaat:

Andere bestanden kunnen ook gelinkt worden, bijvoorbeeld de [[index|homepagina]]! 

> [!tip]
> 
> Probeer in plaats van "De informatie kan [[Links#Bestanden binnen de wiki|hier]] gevonden worden." de relevante woord(en) als link aan te geven bijvoorbeeld:
> > Hier is kennis over het [[Links#Bestanden binnen de wiki|linken van bestanden]] voor nodig.
> 
> Dit maakt het duidelijker voor gebruikers met een screenreader en maakt de tekst gemakkelijker te begruipen.

Tot slot kan de titel van een hoofdstuk ook toegevoegd worden aan een link door een hashtag (`#`) na de bestandsnaam te zetten. Dit kan ook gevolgd worden door een `|` om de tekst te veranderen:

```
Hier is kennis over het [[Links#Bestanden binnen de wiki|linken van bestanden]] voor nodig.
```

Resultaat:

Hier is kennis over het [[Links#Bestanden binnen de wiki|linken van bestanden]] voor nodig.

## Afbeeldingen

Als een afbeelding toegevoegd moet worden, wordt een uitroepteken (`!`) voor de blokhaken (`[]`) van de link geplaatst. Bijvoorbeeld:

```
![Windesheim-logo](https://www.windesheim.nl/getmedia/d06bfafc-febf-4c5e-bcec-bdf619d2ae93/Windesheim_logo.png?width=159&height=102&ext=.png)
```

Resultaat:

![Windesheim-logo](https://www.windesheim.nl/getmedia/d06bfafc-febf-4c5e-bcec-bdf619d2ae93/Windesheim_logo.png?width=159&height=102&ext=.png)
