---
title: Quotes
draft: false
tags:
  - markdown
description: uitleg over het maken van infoblokken en quotes.
date: 2024-01-01
aliases:
  - Infoblokken
  - vragen
  - tips
  - waarschuwing
difficulty: 1
---
In Markdown kunnen quotes worden toegevoegd door een `>` teken aan het begin van de regel te gebruiken. Bijvoorbeeld:

```
> Let your plans be dark as night, and when you're ready, fall like a thunderbolt 

\-Sun Tzu
```

Resultaat:

> Let your plans be dark as night, and when you're ready, fall like a thunderbolt 

\-Sun Tzu

## Infoblokken

Markdown ondersteunt ook infoblokken die gebruikt kunnen worden om informatie op een opvallende manier weer te geven. Dit kan worden gedaan door `[!info]`, `[!tip]` of andere specifieke bloktypes aan het begin van de quote te plaatsen.

Hier is een voorbeeld van een infoblok:

```
> [!info] infoblokken
> Een quote kan ook in een infoblok worden veranderd door er `[!info]` of `[!tip]` voor te zetten. Ook kan de naam van het blok veranderd worden door de naam op de eerste lijn na `]` te zetten.
> > [!example]+ Nested infoblokken zijn ook mogelijk
> > Door een `+` of `-` na de `]` toe te voegen kan deze ook ingevouwen worden.
```

> [!info] infoblokken
> Een quote kan ook in een infoblok worden veranderd door er `[!info]` of `[!tip]` voor te zetten. Ook kan de naam van het blok veranderd worden door de naam op de eerste lijn na `]` te zetten.
> > [!example]+ Nested infoblokken zijn ook mogelijk
> > Door een `+` of `-` na de `]` toe te voegen kan deze ook ingevouwen worden.

### Types/iconen van infoblokken

Er zijn verschillende types en bijbehorende icoontjes die gebruikt kunnen worden voor infoblokken deze worden binnen het \[!\] blok geplaatst. Hier is een lijst van de beschikbare opties (niet hoofdlettergevoelig):


> [!example]- Voorbeeld iconen
> > [!abstract]-
> >Kan ook met `summary` of `tldr` gemaakt worden.
> 
> >[!note]
> 
> >[!info]
> 
> >[!todo]
> 
> >[!tip]-
> > Kan ook met `hint` of `important` gemaakt worden.
> 
> >[!success]-
> > Kan ook met `check` of `done` gemaakt worden.
> 
> >[!failure]-
> > Kan ook met `fail` of `missing` gemaakt worden.
> 
> >[!danger]-
> > Kan ook met `error` gemaakt worden.
> 
> >[!bug]
>
> > [!example]
> 
> > [!quote]-
> > Kan ook met `cite` gemaakt worden


Hier is een voorbeeld van hoe een `tip` blok gemaakt kan worden:

```
> [!tip] Dit is een tip! 
> Tips kunnen handige informatie bevatten die de lezer helpt.
```

Resultaat:

> [!tip] Dit is een tip! 
> Tips kunnen handige informatie bevatten die de lezer helpt.
