---
title: Matrixen
draft: false
tags:
  - LaTeX
description: Uitleg over het maken van matrixen met LaTeX.
date: 2024-01-01
aliases: 
difficulty: 2
---
Binnen LaTeX kan een matrix gemaakt worden. dit kan met behulp van de `\begin{matrix}` en `\end{matrix}` tags die om de tekst van de matrix heen gezet worden. 

De inhoud van de matrix wordt aangeven door `&` tussen de waardes op dezelfde rij te zetten en `\\` om een nieuwe rij te beginnen:

```
$$
\begin{matrix}
a & b \\
c & d
\end{matrix}
$$
```

Resultaat:

$$
\begin{matrix}
a & b \\
c & d
\end{matrix}
$$

Ook zijn er verschillende soorten scheidingstekens mogelijk. deze zijn te selecteren door de start en end tags aan te passen:

```
$$
\begin{Bmatrix}
a & b \\
c & d
\end{Bmatrix}
$$
```

Resultaat:

$$
\begin{Bmatrix}
a & b \\
c & d
\end{Bmatrix}
$$

> [!example]- Matrixen met haakjes
> 
> |**Type**|**Code**|**Resultaat**|
> |:-|:-|:-:|
> |`matrix`|`$\begin{matrix} a & b \\ c & d \end{matrix}$`| $\begin{matrix} a & b \\ c & d \end{matrix}$ |
> |`pmatrix`|`$\begin{pmatrix} a & b \\ c & d \end{matrix}$`| $\begin{pmatrix} a & b \\ c & d \end{pmatrix}$ |
> |`bmatrix`|`$\begin{bmatrix} a & b \\ c & d \end{bmatrix}$ `| $\begin{bmatrix} a & b \\ c & d \end{bmatrix}$ |
> |`Bmatrix`|`$\begin{Bmatrix} a & b \\ c & d \end{Bmatrix}$`|$\begin{Bmatrix} a & b \\ c & d \end{Bmatrix}$ |
> |`vmatrix`|`$\begin{vmatrix} a & b \\ c & d \end{vmatrix}$ `| $\begin{vmatrix} a & b \\ c & d \end{vmatrix}$ |
> |`Vmatrix`|`$\begin{Vmatrix} a & b \\ c & d \end{Vmatrix}$`| $\begin{Vmatrix} a & b \\ c & d \end{Vmatrix}$ |

## Inline matrix

Voor kleine matrixes is het ook mogelijk om `{smallmatrix}` te gebruiken. deze matrix past binnen regels tekst:

```
De matrix is: $\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}$
```

Resultaat:

De matrix is: $\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}$

net zoals bij normale matrixes kunnen p, b, B, v en V hiervoor gezet worden om scheidingstekens toe te voegen.

> [!example]- Smallmatrixen met haakjes
> 
> |**Type**|**Code**|**Resultaat**|
> |:-|:-|:-:|
> |`smallmatrix`|`$\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}$` | $\begin{smallmatrix} a & b \\ c & d \end{smallmatrix}$ |
> |`psmallmatrix`|`$\begin{psmallmatrix} a & b \\ c & d \end{psmallmatrix}$ `| $\begin{psmallmatrix} a & b \\ c & d \end{psmallmatrix}$ |
> |`bsmallmatrix`|`$\begin{bsmallmatrix} a & b \\ c & d \end{bsmallmatrix}$` | $\begin{bsmallmatrix} a & b \\ c & d \end{bsmallmatrix}$ |
> |`Bsmallmatrix`|`$\begin{Bsmallmatrix} a & b \\ c & d \end{Bsmallmatrix}$` | $\begin{Bsmallmatrix} a & b \\ c & d \end{Bsmallmatrix}$ |
> |`vsmallmatrix`|`$\begin{vsmallmatrix} a & b \\ c & d \end{vsmallmatrix}$` | $\begin{vsmallmatrix} a & b \\ c & d \end{vsmallmatrix}$ |
> |`Vsmallmatrix`|`$\begin{Vsmallmatrix} a & b \\ c & d \end{Vsmallmatrix}$` | $\begin{Vsmallmatrix} a & b \\ c & d \end{Vsmallmatrix}$ |

>[!danger] Leesbaarheid smallmatrix
>
>smallmatrix is niet altijd goed leesbaar, probeer hier voor slechtziende gebruikers rekening mee te houden.

## Eigen scheidingstekens

Het is ook mogelijk een (small)matrix te maken met zelfgekozen scheidingstekens. deze kunnen toegevoegd worden aan een normale matrix door deze te omringen met de `\left\scheidingsteken` en `\right\scheidingsteken` tags, deze mogen ook verschillende scheidingstekens hebben zoals in dit voorbeeld:

```
$$
\left\langle\begin{matrix}
a & b & c\\
d & e & f
\end{matrix}\right\rceil
$$
```

Resultaat:

$$
\left\langle\begin{matrix}
a & b & c\\
d & e & f
\end{matrix}\right\rceil
$$

> [!example]- Beschikbare scheidingstekens
> 
> |**Teken**|**Code**|**Resultaat**|
> |:-|:-|:-:|
> |`[]`|`$$\left[ \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right]$$`|$$\left[ \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right]$$|
> |`{}` Vergeet de \\ niet|`$$\left\{ \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\}$$`|$$\left\{ \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\}$$|
> |`()`|`$$\left( \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right)$$`|$$\left( \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right)$$|
> |`langle`|`$$\left\langle \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\langle$$`|$$\left\langle \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\langle$$|
> |`rangle`|`$$\left\rangle \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\rangle$$`|$$\left\rangle \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\rangle$$|
> |`\|`|`$$\left\| \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\|$$`|$$\left\| \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\|$$| 
> |`lceil`|`$$\left\lceil \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\lceil$$`|$$\left\lceil \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\lceil$$|
>|`rceil`|`$$\left\rceil \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\rceil$$`|$$\left\lceil \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\rceil$$|
>|`lfloor`|`$$\left\lfloor \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\lfloor$$`|$$\left\lfloor \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\lfloor$$|
>|`rfloor`|`$$\left\rfloor \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\rfloor$$`|$$\left\lfloor \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right\lfloor$$|
>
> > [!bug]+ `|` kan niet binnen een code blok in een tabel
> > `|`- `$$\left| \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right|$$`-$$\left| \begin{smallmatrix} a & b \\ c & d \end{smallmatrix} \right|$$

