---
title: Fil d'Ariane et navigation
date: 2020-09-15
description: Comment imaginer une navigation simple et efficace sur un site minimal? Pas de menu, un menu simple, autre chose?
images:
- https://cdn.pixabay.com/photo/2017/07/26/16/48/bread-2542308_960_720.jpg
--- 

Un menu simple, un menu étoffé ou pas de menu du tout.
Comment imaginer une navigation efficace sur un site minimal.
La réflexion est en cours; ce site n'est pas assez fourni pour en parler de manière définitive.

## Le nécessaire

Il n'y a que 2 choses qui me paraissent nécessaires sur tout site web:

- la possibilité de revenir sur la page d'accueil à partir de n'importe quelle page du site
- l'absence de pages orphelines (de pages vers lesquelles aucun lien interne ne mène)

Tout le reste est envisageable.
Sur ce site, il est toujours possible de revenir à l'accueil par le titre principal en haut de page.

**Bonne pratique Opquast:** [Il est possible de revenir à la page d'accueil depuis toutes les pages.](https://checklists.opquast.com/fr/qualiteweb/il-est-possible-de-revenir-a-la-page-daccueil-depuis-toutes-les-pages) 

## Structure des URL et pages orphelines

Lorsque les adresses comportent plusieurs termes -- ici: `/blog/breadcrumb/` -- il me semble toujours nécessaire qu'une version raccourcie fonctionne également. 
En conséquence, `/blog/` doit proposer une page.

Cette page qui restait orpheline, ce sont les [archives du blog](/blog/).
Quand le nombre d'articles sera plus important, je me limiterai aux quelques derniers sur la page d'accueil.
Il faudra bien les retrouver tous quelque part.

Plusieurs solutions sont possibles:

- proposer une menu simple avec un lien vers les archives du blog
- proposer quelque part au moins un lien vers les archives du blog
- proposer un fil d'Ariane ou *breadcrumb*

## Le choix du fil d'Ariane

J'ai donc ajouté, en pied de page, un *breadcrumb*.
Ainsi, à partir de chaque page autre que la page d'accueil, il est possible de se rendre directement:

- sur la page d'accueil (par le pied de page en plus du titre du site)
- sur la page d'archives du blog

Même quand la navigation n'est pas profonde -- ici, un seul niveau de répertoire(s) -- c'est une solution qui peut être efficace et élégante.

**Bonne pratique Opquast:** [Chaque page affiche une information permettant de connaître son emplacement dans l'arborescence du site.](https://checklists.opquast.com/fr/qualiteweb/chaque-page-affiche-une-information-permettant-de-connaitre-son-emplacement-dans-larborescence-du-site)

Reste la question de l'accès aux archives du blog à partir de toutes les pages qui ne font pas partie du blog.
Actuellement, seule la page d'accueil est concernée, mais le problème se posera quand je classerai des pages dans d'autres répertoires.

## Un mini-menu

La réponse: un mini-menu en pied de page d'accueil.
Aujourd'hui, il est un peu ridicule avec son seul lien vers le blog.
Mais il s'étoffera automatiquement quand j'ajouterai d'autres rubriques.

Il vaudra la peine de se reposer la question de la pertinence de sa position en bas de page une fois de nouvelles rubriques crées.
En l'état, j'ai le sentiment que le mini-menu en bas de page n'altère pas la lecture des articles.
Un objectif du site, au moins, paraît respecté.

