---
title: Codeblokken
draft: false
tags:
  - markdown
description: uitleg over het toevoegen van (uitvoerbare) codeblokken.
date: 2024-01-01
aliases:
  - code
  - uitvoerbaar
  - sandbox
difficulty: 1
---
In deze wiki kunnen we codeblokken gebruiken om code voorbeelden te tonen. Door bepaalde syntax toe te voegen, kunnen we ook uitvoerbare en bewerkbare codeblokken creëren.

Gebruik de volgende syntax om een codeblok te maken:

~~~
```python
hello = "hello"
print(hello, world := "world")
```
~~~

Resultaat:
```python
hello = "hello"
print(hello, world := "world")
```

Deze blokken worden gemaakt door 3 backticks (\`\`\`) of 3 tildes (\~\~\~) om de code heen te zetten. Ook kan de programmeertaal meegegeven worden na de het openen van het blok. dit moet zonder spatie na het openen en is een naam zoals "python" of "C#".

## Inline codeblokken

voor korte stukjes code zoals een enkel statement kan met behulp van een enkele backtick "\`"

Zin met print statement:

```
Door een extra `Print(i)` toe te voegen...
```

Resultaat:

Door een extra `Print(i)` toe te voegen...
## Uitvoerbare codeblokken

Om een codeblok uitvoerbaar te maken, voeg je "runner" en "sandbox" toe na de naam van de taal. Hierdoor kunnen gebruikers de code direct vanuit de wiki uitvoeren en bewerken.

hier is een runner blok:

~~~
```python runner
hello = "hello"
print(hello, world := "world")
```
~~~

Resultaat: 

```python runner
hello = "hello"
print(hello, world := "world")
```

en een sandbox blok:

~~~
```python runner
hello = "hello"
print(hello, world := "world")
```
~~~

Resultaat:

```python sandbox
hello = "hello"
print(hello, world := "world")
```