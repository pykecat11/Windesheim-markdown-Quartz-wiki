---
title: Comments
draft: false
tags:
  - markdown
description: uitleg over het schrijven van comments binnen de bestanden.
date: 2024-01-01
aliases:
  - onzichtbare text
difficulty: 1
---
In onze wiki kun je commentaar toevoegen dat niet zichtbaar is voor de lezer. Deze comments zijn alleen zichtbaar in de editor en kunnen ook [[Markdown/Effecten|teksteffecten]] bevatten. Dit is handig voor het toevoegen van notities of uitleg voor de redacteuren zonder dat de eindgebruiker deze ziet.

Gebruik de volgende syntax om een commentaar toe te voegen:

```
%%Dit is een commentaar dat normaal niet gezien kan worden%%
```

Resultaat:
%%Dit is een comment dat normaal niet gezien kan worden%%
(je kan het resultaat niet zien omdat dit onzichtbaar is :P)

Deze comments blijven zelfs onzichtbaar binnen code blocks. Dit betekent dat je extra informatie of notities kunt toevoegen in je code zonder dat het de uitvoer beïnvloedt.

```
print("Hallo")
%%Dit commentaar is niet zichtbaar voor de lezer%%
```

%%==dit kan een bug zijn ^==%%
%%==zien comments zichtbaar binnen quartz html source?==%%
## Mermaid

Het is ook mogelijk comments in een [[Mermaid#comments|mermaid]] diagram te zetten. Dit kan met behulp van dubbele procenttekens (`%%`) zoals in dit voorbeeld: