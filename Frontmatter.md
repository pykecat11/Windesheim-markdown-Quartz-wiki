---
title: Frontmatter
draft: false
tags:
  - markdown
description: Uitleg over het toevoegen van attributen aan de pagina door middel van Frontmatter.
date: 2024-01-01
aliases:
  - bestand maken
  - paginanaam
  - metadata
  - tags
  - difficulty
difficulty: 1
---
Frontmatter is de methode die Quartz gebruikt om de metadata van een bestand aan te geven, zoals de titel en tags. Deze metadata helpt bij de organisatie en het beheer van de inhoud binnen de wiki.

Hier is een voorbeeld van hoe frontmatter eruitziet als tekst:

```yaml
---
title: Voorbeeld titel
draft: false
tags:
  - voorbeeld-tag
  - tweede tag
description: voorbeeldbeschrijving van de pagina
date: 2024-02-12
aliases: 
  - Alternatieve naam
  - Andere naam
difficulty: 1
---
```

Quartz ondersteunt verschillende frontmatter tags. Hieronder is een overzicht van de beschikbare tags, hun toepassing en het verwachte formaat:

| **Tag**       | **Toepassing**                                                               | **formaat** |
| :------------ | :--------------------------------------------------------------------------- | :---------- |
| `title`       | De titel van de pagina. Als deze afwezig is, wordt de bestandsnaam gebruikt. | string      |
| `draft`       | Geeft aan of de pagina zichtbaar is binnen de applicatie.                    | bool        |
| `tags`        | De tags van de pagina, gebruikt voor categorisatie en zoekbaarheid.          | string\[\]  |
| `description` | Een beschrijving van de pagina.                                              | string      |
| `date`        | De datum waarop de pagina is geschreven of bewerkt.                          | yyyy-mm-dd  |
| `aliases`     | Alternatieve namen voor de pagina, deze redirecten naar deze pagina.         | string\[\]  |
| `difficulty`  | De moeilijkheidsgraad van de inhoud op de pagina.                            | int         |
%%==voeg betekenis nummers difficulty toe, controleer date > hudige date->onzichtbaar en voeg waarschuwing toe==%%
## Frontmatter binnen obsidian

Als Obsidian wordt gebruikt voor het beheren van de wiki, verandert de frontmatter in een tabel. Let hierbij op dat de datum in het systeemformaat wordt weergegeven.
