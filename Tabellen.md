---
title: tabellen
draft: false
tags:
  - markdown
description: uitleg over het maken en stylen van tabellen.
date: 2024-01-01
aliases: 
difficulty: 1
---
In Markdown kunnen tabellen worden gemaakt met behulp van de volgende syntax:

```
|**kop 1**|**kop 2**|**kop 3**|
|:-|:-:|-:|
|1|2|~~3~~|
|4|~~5~~|6|
```

Resultaat:

| **kop 1** | **kop 2** | **kop 3** |
| :-------- | :-------: | --------: |
| 1         |     2     |     ~~3~~ |
| 4         |   ~~5~~   |         6 |

Binnen de tabellen een pipe (`|`) worden geëscaped met behulp van een backslash (`\`) voorafgaand aan de pipe.

Ook kunnen effecten en links zoals *schuine* of ~~doorstreepte~~ tekst gebruikt worden binnen tabel.
## Alignment van de kolommen

Het alignen van de kolommen kan worden gedaan door het toevoegen van specifieke een dubbele punt (`:`) naast de pipes (`|`). De mogelijkheden zijn: 
- `:-` voor links alignen (default)
- `:-:` voor centreren 
- `-:` voor rechts alignen
