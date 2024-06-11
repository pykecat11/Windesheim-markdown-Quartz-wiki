---
title: Tekst-effecten
draft: false
tags:
  - markdown
description: uitleg over effecten op tekst toepassen.
date: 2024-01-01
aliases:
  - stijl
  - opmaak
difficulty: 1
---
Markdown is een eenvoudige opmaaktaal die vaak gebruikt wordt om tekst op een gestructureerde en overzichtelijke manier weer te geven. Hieronder vind je een overzicht van de basisstijlen en -opmaakopties die binnen onze wiki gebruikt worden, inclusief enkele voorbeelden.

### Doorgestreepte Tekst
Om tekst door te strepen, plaats je twee tildes (~~) aan beide kanten van de tekst.

Voorbeeld:
```
~~doorgestreepte tekst~~
```

Resultaat: ~~doorgestreepte tekst~~

### Schuine Tekst

Om tekst schuin weer te geven, plaats je een sterretje (`*`) of een laag streepje (`_`) aan beide kanten van de tekst.

Voorbeeld:
```
*schuine tekst*
```

Resultaat: *schuine tekst*

### Dikgedrukte tekst

Om tekst dikgedrukt weer te geven, plaats je twee sterretjes (`**`) of twee lage streepjes (`__`) aan beide kanten van de tekst.

Voorbeeld:
```
**dikgedrukte tekst**
```

Resultaat: **dikgedrukte tekst**

### Gemarkeerde tekst
Voor gemarkeerde tekst gebruik je dubbele gelijkteken (`==`) aan beide kanten van de tekst.

Voorbeeld:
```
==gemarkeerde tekst==
```

Resultaat: ==gemarkeerde teskst==

> [!missing] Underlined tekst
> Tekst met een underline is niet beschikbaar binnen markdown, deze tekst is lastig te lezen en wordt geassocieerd met links.

### Combineren van meerdere effecten

Markdown biedt ook de mogelijkheid om verschillende opmaakeffecten te combineren. De volgorde van de effecten maakt hierbij niet uit.

Voorbeeld van doorgestreepte en dikgedrukte tekst:

```
~~__dikgedrukte doorgestreepte tekst__~~
```

Resultaat: ~~__dikgedrukte doorgestreepte tekst__~~

Alternatief voorbeeld:

```
dit gedeelte van de *tekst is schuin ~~en dit is* onderstreept~~
```

Resultaat: dit gedeelte van de *tekst is schuin ~~en dit is* onderstreept~~

### Effecten escapen

Als je de speciale Markdown-karakters letterlijk wilt weergeven, zonder dat ze een effect hebben op de tekst, plaats je een backslash (\\) voor het karakter.

```
\*deze tekst is niet schuin\*
```

Resultaat: \*deze tekst is niet schuin\*
