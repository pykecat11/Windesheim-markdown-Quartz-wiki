---
title: Flowchart
draft: true
tags:
  - mermaid
description: desc
date: 2024-01-01
aliases: 
difficulty: 1
---
Met mermaid kunnen flowcharts gemaakt worden door middel van "flowchart" of "graph" op de eerste lijn te zetten. Binnen deze diagrammen kunnen verschillende [[Mermaid#Punten|punten]] verbonden worden door middel van pijlen.

~~~
```mermaid
flowchart
	A --> B
```
~~~

Resultaat:

```mermaid
flowchart
	A --> B
```

# Punten

## ID als naam

Er zijn meerdere manieren om punten binnen een flowchart aan te geven, de meest simpele manier is door direct de tekst van het punt neer te zetten:

~~~
```mermaid
flowchart
	punt1 --> punt2
```
~~~

Resultaat:

```mermaid
flowchart
	punt1 --> punt2
```

Deze manier is minder flexibel omdat er geen spaties binnen de namen gezet kunnen worden. Ook ontstaan er problemen wanneer er bijvoorbeeld een quote (`"`) aan het begin van de naam komt te staan. 

## Punt met tekst

Voor meer flexibiliteit is het mogelijk om blokhaken (`[]`) met de tekst van het punt na het ID van de node te zetten:

~~~
```mermaid
flowchart
	A[punt A] --> B[punt B]
```
~~~

Resultaat:

```mermaid
flowchart
	A[punt A] --> B[punt B]
```

### Effecten in de tekst

Het is ook mogelijk om [[Markdown/Effecten|effecten]] van markdown toe te passen op de tekst. Dit is mogelijk door een quote en backtick om de tekst binnen de blokhaken (``["` `"]``) te zetten zoals in dit voorbeeld waarin de letters van de punten [[Markdown/Effecten#Dikgedrukte tekst|dikgedrukt]] gemaakt worden:

~~~
```mermaid
flowchart
	A["`Punt **A**`"] --> B["`Punt **B**`"]
```
~~~

Resultaat:

```mermaid
flowchart
	A["`Punt **A**`"] --> B["`Punt **B**`"]
```

### Escapen van karakters

==eeeeeeee #18969376 #8272 GEEN \\==

## Definitie aan het einde
%%==als alle diagrammen dit gebruiken verplaats naar [[Mermaid]] ==%%