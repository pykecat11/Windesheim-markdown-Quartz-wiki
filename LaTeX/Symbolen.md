---
title: Symbolen
draft: false
tags:
  - voorbeeld-tag
  - tweede
  - tag
description: Uitleg over het gebruiken van symbolen binnen LaTeX.
date: 2024-01-01
aliases: 
difficulty: 1
---

## Reken operatoren

de meeste basisoperatoren (+, -, =, <, >) zijn als tekst binnen LaTeX te gebruiken. vermenigvuldiging, niet gelijk aan en deling moeten met een \\ aangegeven worden zoals in het tabel hieronder:

| **Type**          | **Notatie**                   | **Resultaat**               |
| :---------------- | :---------------------------- | :-------------------------- |
| Basisoperatoren   | `$a + b$`                     | $a + b$                     |
| Vermenigvuldiging | `$a \times b$` of `a \cdot b` | $a \times b$ of $a \cdot b$ |
| Niet gelijk aan   | `$a \neq b$`                  | $a \neq b$                  |
| Deling            | `$a \div b$`                  | $a \div b$                  |

>[!tip] Deling en fracties
>
> Voor betere leesbaarheid en consistentie is het aangeraden om [[Uitdrukkingen#Fracties|fracties]] in plaats van deling te gebruiken, vooral in grotere functies. Dit voorkomt onduidelijkheden en is consistent met de conventies.

## Niet-Latijnse karakters 

Er kunnen ook alternatieve symbolen zoals $\pi$ of $\ohm$ gebruikt worden in latex. Deze worden aangegeven door een backslash (`\`) gevolgd door de naam van de letter binnen een LaTeX blok. als de eerste letter van de naam van een Griekse letter een hoofdletter is word de hoofdletter in plaats van de kleine letter gebruikt.

```
Met behulp van LaTeX kunnen symbolen zoals $\aleph$ en $\Delta$ gemakkelijk gebruikt worden!
```

Resultaat:

Met behulp van LaTeX kunnen symbolen zoals $\aleph$ en $\Delta$ gemakkelijk gebruikt worden!

> [!example]- Lijst van karakters
> 
> Door de eerste letter een hoofdletter te maken wordt de hoofdletter gebruikt:
>  `delta`$\delta$ $\rightarrow$ `Delta` $\Delta$
> Dit is niet beschikbaar voor elke letter omdat sommige letters hetzelfde zijn als in het latijnse alfabet.
>  
> |**Letter**|**Notitie**|**Resultaat**|**Hoofdletter**|
> |:-|:-|:-|:-|
> |Alpha|`$\alpha$`|$\alpha$|(Latijns) $A$|
> |Beta|`$\beta$`|$\beta$|(Latijns) $B$|
> |Gamma|`$\gamma$`|$\gamma$|$\Gamma$|
> |Delta|`$\delta$`|$\delta$|$\Delta$|
> |Epsilon|`$\epsilon$`|$\epsilon$|(Latijns) $E$|
> |Zeta|`$\zeta$`|$\zeta$|(Latijns) $Z$|
> |Eta|`$\eta$`|$\eta$|(Latijns) $H$|
> |Theta|`$\theta$`|$\theta$|$\Theta$|
> |Iota|`$\iota$`|$\iota$|(Latijns) $I$|
> |Kappa|`$\kappa$`|$\kappa$|(Latijns) $K$|
> |Lambda|`$\lambda$`|$\lambda$|$\Lambda$|
> |Mu|`$\mu$`|$\mu$|(Latijns) $M$|
> |Nu|`$\nu$`|$\nu$|(Latijns) $N$|
> |Xi|`$\xi$`|$\xi$|$\Xi$|
> |Omicron|`$\omicron$`|$\omicron$|(Latijns) $O$|
> |Pi|`$\pi$`|$\pi$|$\Pi$|
> |Rho|`$\rho$`|$\rho$|(Latijns) $P$|
> |Sigma|`$\sigma$`|$\sigma$|$\Sigma$|
> |Tau|`$\tau$`|$\tau$|(Latijns) $T$|
> |Upsilon|`$\upsilon$`|$\upsilon$|$\Upsilon$|
> |Phi|`$\phi$`|$\phi$|$\Phi$|
> |Chi|`$\chi$`|$\chi$|(Latijns) $X$|
> |Psi|`$\psi$`|$\psi$|$\Psi$|
> |Omega|`$\omega$`|$\omega$|$\Omega$|
> 
> Van het Hebreeuwse alfabet zijn alleen de eerste 4 letters beschikbaar in LaTeX.
> 
> |**Letter**|**Notitie**|**Resultaat**|
> |:-|:-|:-|
> |Aleph|`$\aleph$`|$\aleph$|
> |Beth|`$\beth$`|$\beth$|
> |Gimel|`$\gimel$`|$\gimel$|
> |Daleth|`$\daleth$`|$\daleth$|

