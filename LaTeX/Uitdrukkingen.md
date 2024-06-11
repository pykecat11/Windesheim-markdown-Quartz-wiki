---
title: Uitdrukkingen
draft: false
tags: 
description: Uitleg over uitdrukkingen zoals machten en fracties binnen LaTeX.
date: 2024-01-01
aliases:
  - wortels
  - fracties
  - machten
  - logartime
difficulty: 1
---

Functies in latex zoals machten en fracties maken gebruik van accolades (`{}`), binnen deze kunnen ook andere uitdrukkingen gezet worden om op deze manier meerdere functies te combineren:

```
$$
T = \sqrt{2\times\frac{Hoogte}{Versnelling}}
$$
```

Resultaat:

$$
T = \sqrt{2\times\frac{Hoogte}{Versnelling}}
$$

### Fracties

Een fractie kan binnen LaTeX aangegeven worden met behulp van de `\frac` tag gevolgd door 2 paar accolades (`{}`). De inhoud van de eerste accolade verschijnt boven de deelstreep terwijl de inhoud van de tweede accolade onder de deelstreep komt.

```
De dichtheid is te berekenen met: $\frac{Gewicht}{Volume}$
```

Resultaat:

De dichtheid is te berekenen met: $\frac{Gewicht}{Volume}$

### Machten

Machten kunnen met behulp van een caret-symbool (`^`) aangegeven worden. Het getal of stuk tekst links wordt het grondtal en de tekst rechts van het symbool wordt de exponent.

```
$2^{16}$
```

Resultaat:

$2^{16}$

### Wortels

wortels kunnen gemaakt worden met behulp van do `\sqrt` tag, deze zet het getal of stuk tekst binnen de eerstvolgende accolades (`{}`) of getal onder een wortel:

```
$$
\sqrt{15}
$$
```

Resultaat:

$$
\sqrt{15}
$$

Het is ook mogelijk een exponent mee te geven. Deze kan meegegeven worden door binnen vierkante haakjes (`[]`) een getal mee te geven. Deze worden na de tag maar voor de radicand (getal waarvan wortel genomen wordt):

```
$$
\sqrt[4]{256}
$$
```

$$
\sqrt[4]{256}
$$

### Logaritmes

Binnen LaTeX kunnen logaritmes gecreëerd worden met behulp van do `\log` tag. Een basis kan meegegeven worden na een underscore (`_`) voor het argument van het logaritme.

$$
log_{10}(100)
$$

>[!tip] Basis van logaritmes
>
>Probeer altijd een basis mee te geven aan een logaritme. Dit voorkomt verwarring omdat de "standaard" basis 10 of $e$ kan zijn.

### Sommatie en Product

Sommatie en Producten kunnen gemaakt worden met de `\sum` en `\prod` tags. Met behulp van een underscore (`_`) en caret-symbool (`^`) kunnen de term en index respectievelijk aangegeven worden:

```
$$
\sum_{i=0}^{5}i*2
$$
$$
\prod_{i=1}^{5}i*3
$$
```

Resultaat:

$$
\sum_{i=0}^{5}i*2
$$
$$
\prod_{i=1}^{5}i*3
$$
