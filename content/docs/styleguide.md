---
title: Guide de style
description: Utilisation de tous les styles disponibles pour tester la feuille de style CSS du site.
draft: true
---

Dans ce billet, j'essaie d'utiliser toutes les mises en page qui seront disponibles ici.
Intertitres de différents niveaux, listes, citations, images et tableaux.
En plus de variations dans le corps du texte.

Cette page permet donc de tester le résultat du balisage avec markdown et la feuille de style (CSS) du site.

## Paragraphes (tu sais, le machin: §)

Un simple paragraphe sans trop d'imagination, avec quelques lignes pour en donner une bonne illustration.
Un simple paragraphe sans trop d'imagination, avec quelques lignes pour en donner une bonne illustration.
Un simple paragraphe sans trop d'imagination, avec quelques lignes pour en donner une bonne illustration.
Un simple paragraphe sans trop d'imagination, avec quelques lignes pour en donner une bonne illustration.

Et le même, avec un saut de ligne artificiel. 
Un simple paragraphe avec saut de ligne artificiel pour en donner une bonne illustration.  
Un simple paragraphe avec saut de ligne artificiel pour en donner une bonne illustration.
Un simple paragraphe avec saut de ligne artificiel pour en donner une bonne illustration.

## Gras, italiques et compagnie

Un texte en **gras** met en exergue, l'*italique* souligne avec plus de finesse.
Quand au ***gras italique***, je te laisse deviner, ami lecteur.
Sans compter les ***variations* possibles** qui n'en ***finissent** pas*.
Amusant, non?

## Citations et notes de bas de page[^notes]

On essaie Proust?

> Longtemps, je me suis couché de bonne heure. Parfois, à peine ma bougie éteinte, mes yeux se fermaient *si vite* que je n’avais **pas le temps** de me dire: «Je m’endors[^2].» Et, une demi-heure après, la pensée qu’il était temps de chercher le sommeil m’éveillait...[^1]

[^notes]: L'affichage des notes n'a aucun `CSS` pour le moment. Je ne les utilise pas...
[^1]: C'est du Proust... raccourci.
[^2]: Eh, bien! Il ne me reste qu'à te souhaiter une bonne nuit, mon chez Marcel. Et surtout ne te réveille pas trop tôt.

## Et une image, ça de dit, Raoul?

Inclusion en markdown classique:

![Flamand rose sur fond rose](https://cdn.pixabay.com/photo/2020/08/29/14/39/flamingo-5527232_960_720.jpg "Mon ami le rose (et le flamand)")

[À compléter, notamment pour responsive design.]

## Listes

### Listes simples

Les listes simples:

- liste
- à puces
- simple

et:

1. liste
1. numérotée
1. simple

### Listes longues

Ainsi que des listes un peu *plus abouties* qui peuvent comporter -- ce n'est qu'un **exemple** -- quelques paragraphes.

- Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.
  La chose, c'est la liste.
- La chose, c'est la liste.
  Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.

Ainsi que le liste un peu *numérotée* qui peut comporter -- ce n'est toujours qu'un **exemple** *parmi d'autres* -- quelques paragraphes.

1. Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.
  La chose, c'est la liste.
1. La chose, c'est la liste.
  Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.

### Et listes complexes

Les puces:

- Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.
  La chose, c'est la liste.
  - Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
    Je répète: **tester** la *mise en page* de la chose.
    La chose, c'est la liste.
  - Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
    Je répète: **tester** la *mise en page* de la chose.
    La chose, c'est la liste.
- Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
  Je répète: **tester** la *mise en page* de la chose.
  La chose, c'est la liste.
  
La même, numérotée:

1. Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
   Je répète: **tester** la *mise en page* de la chose.
   La chose, c'est la liste.
    1. Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
       Je répète: **tester** la *mise en page* de la chose.
       La chose, c'est la liste.
    1. Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
       Je répète: **tester** la *mise en page* de la chose.
       La chose, c'est la liste.
1. Liste à puces simple, mais avec des textes un peu plus longs, afin de tester la mise en page de la chose.
   Je répète: **tester** la *mise en page* de la chose.
   La chose, c'est la liste.

### Liste de définition

Malheureusement sous utilisée, elle est pertinente d'un point de vue sématique.
Et efficace à la lecture.

Le terme
: La définition

Exemple plus complexe
: Une liste un peu bizarre, sous utilisée en HTML.
: Seconde définition pour le même terme.

Autre exemple
Deux termes
: Et une seule définition  
  (avec un saut de ligne manuel)
  
## Quelques liens

Simplement copié et collé: https://minimal-website.ch et voilà.
Mais on pourrait aussi faire mieux, par exemple: [Minimal Website](https://minimal-website.ch).
Et encore mieux avec un `title`: [Minimal Website](https://minimal-website.ch "Un site web minimal et efficace.") (survole avec ta souris...).

## Le tableau

Allez, on fait simple. 
Un tableau de données utile, avec des alignements à gauche, au centre et à droite.

| Canton | Abréviation | Population |
|:-------|:-----------:|-----------:|
| Zurich | ZH | 1520968|
| Neuchâtel | NE | 176850 |

[À suivre: § dans le tableau et reste de responsive.]

## Le code

Évidemment, il y a le petite machin `en ligne`, comme ici.
Et le gros extrait de code.
En python:

```python
def fact(n):
    if n<2:
        return 1
    else:
        return n*fact(n-1)
```
Et un extrait de template HTML de Go:

```go-html-template
{{ if .Description }}
  <meta name="description" content="{{ .Description }}">
{{ end }}

<link rel="alternate" type="application/rss+xml" href="{{ .Site.BaseURL }}index.xml" title="{{ .Site.Title }}">
{{ template "_internal/opengraph.html" . }}
```

Joli, non?