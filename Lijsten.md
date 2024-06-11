---
title: lijsten
draft: false
tags:
  - markdown
description: uitleg over het maken van verschillende soorten lijsten.
date: 2024-01-01
aliases:
  - punten
difficulty: 1
---
Markdown biedt verschillende manieren om lijsten weer te geven, zoals normale lijsten en checklijsten.

## Normale lijsten

Normale lijsten kunnen worden gemaakt met behulp van asterisken (`*`) of minnen (`-`). Ook is het mogelijk om nummers te gebruiken.

Voorbeeld:

```
- 1
- 2
* 3

1. 1 
2. 2 
3. 3
```

Resultaat:

- 1
- 2
* 3

1. 1 
2. 2 
3. 3

## Geneste lijsten

Deze lijsten kunnen ook genest zijn. Bijvoorbeeld:

```
- 1
	- 1.1
	- 1.2

1. 1
	1. 1.1
	2. 1.2
	3. 1.3
2. 2
	1. 2.1
	2. 2.2
```

Resultaat:

- 1
	- 1.1
	- 1.2

1. 1
	1. 1.1
	2. 1.2
	3. 1.3
2. 2
	1. 2.1
	2. 2.2

## Checklijsten

Checklijsten kunnen worden gemaakt door blokhaken met een spatie (`[ ]`) toe te voegen na de min (`-`) of asterisk (`*`). Deze items van de lijst kunnen afgevinkt worden. Door een x binnen de blokhaken te zetten (`[x]`) wordt de tekst van het item zelf ook doorstreept. Wanneer er een ander karakter in wordt gezet zal de doos alleen afgevinkt worden zoals in dit voorbeeld te zien is:

```
- [ ] 1
- [x] 2
* [-] 3
```

Resultaat:

- [ ] 1
- [x] 2
* [-] 3
