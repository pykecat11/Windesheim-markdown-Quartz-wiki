---
title: LaTeX-notatie
draft: false
tags:
  - LaTeX
description: Basis van de LaTeX notatie binnen markdown.
date: 2024-01-01
aliases:
  - matrix
difficulty: 1
---
Markdown biedt ondersteuning voor het invoegen van LaTeX-formules, waardoor wetenschappelijke en wiskundige notaties eenvoudig in documenten kunnen worden opgenomen.

## Inline LaTeX

Korte formules kunnen binnen een tekstregel weergeven worden. Door dollartekens (`$`) om de formule heen te zetten wordt de tekst binnen de tekens als formule gezien zoals in dit voorbeeld:

```
De reden waarom er maximaal $0.1\micro g\cdot{kg}^{-1}$ PFAS in de grond mag zitten is omdat dit de laagste meetbare hoeveelheid was toen de wet werd aangenomen.
```

Resultaat:

De reden waarom er maximaal $0.1\micro g\cdot{kg}^{-1}$ PFAS in de grond mag zitten is omdat dit de laagste meetbare hoeveelheid was toen de wet werd aangenomen.

Dit voorbeeld is gemaakt met [[Uitdrukkingen#Machten|machten]].

## Blok LaTeX

Grotere en complexere formules kunnen niet altijd binnen een stuk tekst, daarom is het ook mogelijk een blok met de formule te maken. dit wordt gedaan door 2 dollartekens (`$$`) om de formule heen te zetten:

```
Om het nulpunt van de parabool te vinden kan de abc-formule toegepast worden:
$$
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$
```

Resultaat:

Om het nulpunt van de parabool te vinden kan de abc-formule toegepast worden:
$$
x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

Dit voorbeeld is gemaakt met behulp van [[Uitdrukkingen#Fracties|fracties]], [[Uitdrukkingen#Machten|machten]] en [[Uitdrukkingen#Wortels|wortels]].

## Variabelen en nummers

Binnen latex worden accolades (`{}`) gebruikt om aan te geven dat een aantal nummers of variabelen bij elkaar hoort, Als er bijvoorbeeld 2^16 opgeschreven wordt zal LaTeX 2 tot de eerste macht vermenigvuldigd met 6 opschrijven. Dit kan voorkomen worden door de 16 binnen deze haakjes te zetten:

```
$2^16$ is geen hoog getal, daarentegen is $2^{16}$ veel hoger.
```

Resultaat:

$2^16$ is geen hoog getal, daarentegen is $2^{16}$ veel hoger.