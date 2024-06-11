---
title: (latex) Effecten
draft: false
tags:
  - LaTeX
description: Uitleg over het gebruiken van teksteffecten binnen LaTeX.
date: 2024-01-01
aliases: 
difficulty: 1
---

LaTeX heeft net [[Effecten|zoals markdown]] zijn eigen effecten. in dit hoofdstuk worden een aantal van deze elementen behandeld.

##### Tekst

Om tekst die geen variabel is er als normale text uit te laten zijn kan deze met behulp van de `\text` tag gevolgd door een paar accolades (`{}`) teruggezet worden tot normale text, dit kan erg handig zijn wanneer er met [[LaTeX/Effecten#Braces|underbraces]] gewerkt wordt:

```
$Deze tekst ziet er niet helemaal juist uit, \text{misschien kan de \\text tag deze terugzetten.}$
```

Resultaat:

$Deze tekst ziet er niet helemaal juist uit, \text{misschien kan de \\text tag deze terugzetten.}$

##### boven en onder-streep
Om herhalende kommagetallen, complementen en gemiddelden te noteren kan er gebruik gemaakt worden van een bovenstreep. Deze maakt gebruik van de `\overline` tag gevolgd door de te bewerken tekst of nummers:

```
$$
\frac{10}{24} = 0.41\overline{6}
$$
```

Resultaat:

$$
\frac{10}{24} = 0.41\overline{6}
$$

Net zoals een bovenstreep is er ook een onderstreep, deze kan gebruikt worden voor vectoren en het onderstrepen van variabelen. Net zoals een bovenstreep wordt deze aangegeven met de `\underline` tag:

```
$$
\underline{v} = \begin{pmatrix} 3 \\ -4 \\ 1 \end{pmatrix}
$$
```

Resultaat:

$$
\underline{v} = \begin{pmatrix} 3 \\ -4 \\ 1 \end{pmatrix}
$$

##### pijlen

Een vaker voorkomende notatie voor vectoren zijn pijlen. LaTeX beschikt ook over pijlen, net zoals over en underlines kunnen deze met de `\overrightarrow` en `\overleftarrow` aangegeven worden.

> [!example]- Voorbeeld vectorpijlen
> 
> `Pijl naar $\overleftarrow{links}$ en naar $\overrightarrow{rechts}$`
> 
> Resultaat:
> 
> Pijl naar $\overleftarrow{links}$ en naar $\overrightarrow{rechts}$

###### Dakjes en tildes

Deze effecten kunnen gebruikt worden om geschatte variabelen en de Fourier-analyse aan te geven. Dit gaat met behulp van de `widehat` en `widetilde` tags gevolgd door de tekst waar het effect nodig is.

>[!example]- Voorbeeld dakjes en tildes
>Schattingen kunnen aangegeven worden met een $\widehat{}$.
>```
>$\widehat{Y} = a + bx$
>```
>
>Resultaat:
>
>$\widehat{Y} = a + bx$
>
> Geschatte waardes kunnen aangegeven worden met een $\widetilde{}$.
> ```
> $\widetilde{x} = 170$
> ```
> 
> Resultaat:
> 
> $\widetilde{x} = 170$

##### Braces

Braces kunnen gebruikt worden om extra context te geven in een formule, dit kan bijvoorbeeld bij een onderdeel van een formule of bij sommatie. Zoals de andere effecten kunnen deze aangeroepen worden met `\overbrace` en `\underbrace` gevolgd door een underscore (`_`) of caret-symbool (`^`) met de tekst respectievelijk.

>[!example]- Voorbeeld braces
>Braces kunnen gebruikt worden om een deel van een formule duidelijker te maken:
>```
>$Y = \underbrace{a + bx}_{\text{formule van de lijn}}$
>```
>
>Resultaat:
>
>$Y = \underbrace{a + bx}_{\text{formule van de lijn}}$
>
>Of voor extra uitleg bij een sommatie.
>```
>$$\sum_{i=1}^{\overbrace{n}^{\text{Aantal}}} i^2$$
>```
>
>Resultaat:
>
>$$\sum_{i=1}^{\overbrace{n}^{\text{Aantal}}} i^2$$

