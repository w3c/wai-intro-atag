---
# translation notes are after "#" in this section

title: "Vue d'ensemble des Règles d'accessibilité pour les outils d'édition (ATAG)"
nav_title: "Vue d'ensemble des ATAG"
ref: /standards-guidelines/atag/   # Translators, do not change this

github:
  repository: w3c/wai-intro-atag
  path: content/index.fr.md    # Add the language shortcode to the middle of the filename, for example: index.fr.md
permalink: /standards-guidelines/atag/fr  # Add the language shortcode to the end, with no slash at end, for example: /standards-guidelines/atag/fr

lang: fr   # Change "en" to the translated language shortcode
last_updated: 2020-12-07   # Put the date of this translation YYYY-MM-DD (with month in the middle)
translators:   # remove from the beginning of the line: "# " and add your name(s)
- name: "Sofia Ahmed"
contributors:
- name: "Sandra Velarde Gonzalez (ETNIC)"

layout: default
feedbackmail: wai@w3.org
footer: |
  <p><strong>Date :</strong> Mise à jour : 1 juillet 2020. Première publication en juillet 2005.</p>
  <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/shawn">Shawn Lawton Henry</a>.</p>
  <p>Développé avec les données du Groupe de travail Éducaton et la Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) et le Groupe de travail pour les Règles d'accessibilité pour les outils d'édition (<a href="https://www.w3.org/WAI/AU/">AUWG</a>).</p>

---


{::nomarkdown}
{% include box.html type="start" h="2" title="Résumé" class="full" %}
{:/}

Cette page introduit le standard Web "Règles d'accessibilité pour les outils d'édition (ATAG)".

Liens rapides vers d'autres ressources :
* [Les ATAG en un coup d'oeil](http://www.w3.org/WAI/intro/atag-glance)
* [Le standard ATAG 2.0](http://www.w3.org/TR/ATAG20/)
* [Mise en pratique d'ATAG 2.0](http://www.w3.org/TR/IMPLEMENTING-ATAG20/)
* [Outil de reporting ATAG](https://www.w3.org/WAI/atag/report-tool/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Table des matières" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Les outils d'édition et les ATAG

Les outils d'édition sont des logiciels et des services que les "auteurs" (développeurs, designers, rédacteurs, etc.) utilisent pour produire du contenu Web (des pages Web statiques, des applications Web dynamiques, etc.). Vous trouverez une liste d'exemple d'outils d'édition dans la rubrique ci-dessous [À qui sont destinées les ATAG](#who-atag-is-for)".

Les documents sur les Règles d'accessibilité pour les outils d'édition (ATAG) expliquent comment :

-   rendre les outils d'édition eux-mêmes accessibles pour permettre aux personnes handicapées de créer du contenu Web, ***et***
-   accompagner les auteurs dans la création de contenu Web plus accessible  — et plus particulièrement :
    rendre possible, soutenir et promouvoir la production de contenus conformes aux Règles pour l'accessibilité des contenus Web    ([WCAG]({{ "/standards-guidelines/wcag/" | relative_url }})).

Les ATAG font partie d'une série de règles pour l'accessibilité, dont les Règles pour l'accessibilité des contenus Web (WCAG) et les Règles pour l'accessibilité des agents utilisateurs (UAAG). [Composants essentiels de l'accessibilité Web]({{ "/fundamentals/components/" | relative_url }}) explique la relation entre les différentes règles.

## À qui sont destinées les ATAG

Les ATAG sont premièrement destinées aux développeurs d'outils d'édition, dont les types d'outils d'édition suivants :

-   les outils d'édition de page Web, par exemple, les éditeurs HTML "WYSIWYG" ("what-you-see-is-what-you-get" : ce que vous voyez est ce que vous obtenez)
-   les logiciels de création de site Web, par exemple, les systèmes de gestion de contenu (CMS) et les systèmes de gestion de l'apprentissage (LMS), les didacticiels, les agrégateurs de contenu
-   les logiciels qui convertissent les technologies de contenu Web, par exemple, les logiciels de traitement de texte et d'autres applications de documents Office avec des fonctionnalités telles que "enregistré sous HTML" ou "enregistré sous EPUB"
-   les outils d'édition multimédias
-   les sites Web qui permettent aux utilisateurs d'ajouter du contenu, tels que les blogues, les sites wiki, les plateformeS de partage de photos, les forums en ligne et les sites de réseaux sociaux
-   d'autres types d'outils sont listés dans le glossaire des [outils d'édition](http://www.w3.org/TR/ATAG20/#def-Authoring-Tool)

Les ATAG et les ressources relatives à celles-ci cherchent également à répondre aux besoins d'une grande variété de publics, y compris les décideurs et les responsables d'entreprise, entre autres.
Par exemple :

-   Les personnes qui veulent opter pour des [outils d'édition](http://www.w3.org/WAI/impl/software) accessibles et qui produisent du contenu accessible peuvent utiliser les ATAG pour évaluer les outils d'édition
-   Les personnes qui souhaitent encourager le développeur de leur outil d'édition déjà existant à améliorer l'accessibilité pour les versions futures peuvent proposer au fournisseur de l'outil d'édition de se référer aux ATAG.

## Que contient la recommandation ATAG 2.0

[**ATAG 2.0**](http://www.w3.org/TR/ATAG20/) est constitué de deux parties principales :

-   La partie A explique comment rendre un outil d'édition lui-même accessible.
-   La partie B explique comment l'outil d'édition peut aider les auteurs à produire un contenu accessible.

**ATAG 2.0** est organisé en couches :

-   Les **principes** permettent d'organiser les règles de façon macroscopique.
-   Les **règles** fournissent un modèle et des objectifs pour les critères de succès.
-   **Les critères de succès sont les recommandations en accessibilité**, rédigées sous forme de déclarations testables, à [trois niveaux](http://www.w3.org/TR/ATAG20/#intro_understand_levels_conformance):
    A, AA, AAA.

[**Les ATAG en un coup d'oeil**](http://www.w3.org/WAI/intro/atag-glance) fournit un bref résumé des principes et des règles d'accessibilité dans l'ATAG 2.0.

[**Mise en pratique d'ATAG 2.0**](http://www.w3.org/TR/IMPLEMENTING-ATAG20/)
est un document informatif complémentaire qui a pour but d'aider les lecteurs à comprendre et à appliquer les ATAG. Mise en pratique d'ATAG 2.0 fournit une justification pour chaque règle ; et pour chaque critère de succès, la recommandation ATAG 2.0 fournit des explications complémentaires sur les objectifs des critères de succès, des exemples, et des liens vers d'autres ressources.

## L'outil de reporting ATAG

L'[**outil de reporting ATAG**](https://www.w3.org/WAI/atag/report-tool/) aide les évaluateurs à faire un rapport de l'accessibilité des outils d'édition. Ils vous guide à travers les recommandations ATAG, vous permet d'enregistrer vos résultats d'évaluation pour chaque recommandation, et génère un rapport sur la conformité ATAG de l'outil d'édition.

## Les versions ATAG : 1.0 et 2.0

ATAG 2.0 est une recommandation du W3C. Cela signifie qu'ATAG 2.0 est un standard abouti, qui a reçu les commentaires du public, dont la mise en pratique a été entièrement testée, qui a démontré des exemples de produits rendus plus accessibles grâce à la mise en pratique d'ATAG 2.0, et qui a été approuvé par les membres du W3C. (Ces étapes sont expliquées dans la section
[Comment la WAI élabore les règles d'accessibilité selon le processus du W3C](http://www.w3.org/WAI/intro/w3c-process).)

[Les Règles d'accessibilité pour les outils d'édition 1.0](http://www.w3.org/TR/2000/REC-ATAG10-20000203/) ont été approuvées en février 2000. Bien qu'ATAG 1.0 soit un standard valable, il est dépassé.
ATAG 2.0 est le standard actuel.

## Traductions

La traduction agréée d'ATAG 2.0 en chinois simplifié est disponible sur cette page : [无障碍创作工具指南(ATAG) 2.0](https://www.w3.org/Translations/ATAG20-zh/).

## Qui élabore les ATAG

Les ATAG ont été élaborées par le Groupe de travail pour les Règles d'accessibilité pour les outils d'édition ([ATAG WG](http://www.w3.org/WAI/AU/)), qui fait partie  de l'Initiative pour l'accessibilité Web ([WAI](http://www.w3.org/WAI/)) du World Wide Web Consortium ([W3C](http://www.w3.org/)). Pour plus d'informations sur le groupe de travail, allez sur la page du [AUWG](http://www.w3.org/WAI/AU/).

[Comment la WAI élabore les Règles d'accessibilité selon le processus du W3C : étapes importantes et opportunités pour contribuer](http://www.w3.org/WAI/intro/w3c-process) décrit les périodes officielles destinées à la révision du public. Les opportunités pour réviser et commenter les documents de la WAI sont annoncées sur la [page d'accueil de la WAI](http://www.w3.org/WAI/)
et sur la liste d'e-mail [Groupe d'intérêt de la WAI](http://www.w3.org/WAI/IG/). Vous trouverez l'adresse e-mail permettant d'envoyer des commentaires dans la section "Statut de ce document".

Les opportunités pour contribuer aux ATAG et autres travaux de la WAI sont introduites sur la page [Participer à la WAI](http://www.w3.org/WAI/participation).
