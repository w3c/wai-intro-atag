---
# translation notes are after "#" in this section

title: "Vue d'ensemble des Règles d'accessibilité pour les outils d'édition (ATAG)"
nav_title: "Vue d'ensemble des ATAG"
ref: /standards-guidelines/atag/   # Translators, do not change this

github:
  repository: w3c/wai-intro-atag
  path: index.fr.md    # Add the language shortcode to the middle of the filename, for example: index.fr.md
permalink: /standards-guidelines/atag/fr  # Add the language shortcode to the end, with no slash at end, for example: /standards-guidelines/atag/fr

lang: fr   # Change "en" to the translated language shortcode
last_updated: 2020-12-07   # Put the date of this translation YYYY-MM-DD (with month in the middle)
# translators:   # remove from the beginning of the line: "# " and add your name(s)
# - name: Translator 1's Name

layout: default
feedbackmail: wai@w3.org
footer: |
  <p><strong>Date :</strong> Mise à jour : 1 juillet 2020. Première publication en juillet 2005.</p>
  <p><strong>Rédactrice :</strong> <a href="http://www.w3.org/People/shawn">Shawn Lawton Henry</a>.</p>
  <p>Développé avec les données du Groupe de travail pour l'Éducaton et la Promotion (<a href="http://www.w3.org/WAI/EO/">EOWG</a>) et le Groupe de travail pour les Règles d'accessibilité pour les outils d'édition (<a href="https://www.w3.org/WAI/AU/">AUWG</a>).</p>

---


{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces the Authoring Tool Accessibility Guidelines (ATAG) web standard.

Quick links to resources:
* [ATAG at a Glance](http://www.w3.org/WAI/intro/atag-glance)
* [ATAG 2.0 Standard](http://www.w3.org/TR/ATAG20/)
* [Implementing ATAG 2.0](http://www.w3.org/TR/IMPLEMENTING-ATAG20/)
* [ATAG Report Tool](https://www.w3.org/WAI/atag/report-tool/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include_cached toc.html type="start" title="Page Contents" %}
{:/}

-   TOC is created automatically.
{:toc}

{::nomarkdown}
{% include_cached toc.html type="end" %}
{:/}

## Authoring Tools and ATAG

Authoring tools are software and services that "authors" (web
developers, designers, writers, etc.) use to produce web content (static
web pages, dynamic web applications, etc.). Examples of authoring tools
are listed below under "[Who ATAG is for](#who-atag-is-for)".

The Authoring Tool Accessibility Guidelines (ATAG) documents explain how
to:

-   make the authoring tools themselves accessible, so that people with
    disabilities can create web content, ***and***
-   help authors create more accessible web content — specifically:
    enable, support, and promote the production of content that conforms
    to Web Content Accessibility Guidelines
    ([WCAG]({{ "/standards-guidelines/wcag/" | relative_url }})).

ATAG is part of a series of accessibility guidelines, including the Web
Content Accessibility Guidelines (WCAG) and the User Agent Accessibility
Guidelines (UAAG). [Essential Components of Web
Accessibility]({{ "/fundamentals/components/" | relative_url }}) explains the
relationship between the different guidelines.

## Who ATAG is for

ATAG is primarily for developers of authoring tools, including the
following types of authoring tools:

-   web page authoring tools, for example, what-you-see-is-what-you-get
    (WYSIWYG) HTML editors
-   software for generating websites, for example, content management
    systems (CMS) and learning management systems (LMS), courseware tools, content aggregators
-   software that converts to web content technologies, for example,
    word processors and other office document applications with Save as
    HTML or EPUB
-   multimedia authoring tools
-   websites that let users add content, such as blogs, wikis, photo
    sharing sites, online forums, and social networking sites
-   other types of tools listed in the glossary definition of [authoring
    tools](http://www.w3.org/TR/ATAG20/#def-Authoring-Tool)

ATAG and supporting resources are also intended to meet the needs of
many different audiences, including policy makers, managers, and others.
For example:

-   People who want to [choose authoring
    tools](http://www.w3.org/WAI/impl/software) that are accessible and
    that produce accessible content can use ATAG to evaluate authoring
    tools.
-   People who want to encourage their existing authoring tool developer
    to improve accessibility in future versions can refer the authoring
    tool vendor to ATAG.

## What is in ATAG 2.0

[**ATAG 2.0**](http://www.w3.org/TR/ATAG20/) has two main parts:

-   Part A is about making the authoring tool itself accessible.
-   Part B is about the authoring tool helping authors produce
    accessible content.

**ATAG 2.0** is organized in layers:

-   **Principles** provide high-level organization for the guidelines.
-   **Guidelines** provide the framework and objectives for the success
    criteria.
-   **Success criteria are the accessibility requirements**, which are
    written as testable statements, at [three
    levels](http://www.w3.org/TR/ATAG20/#intro_understand_levels_conformance):
    A, AA, AAA.

[**ATAG at a Glance**](http://www.w3.org/WAI/intro/atag-glance) provides
a short summary of the accessibility principles and guidelines in ATAG
2.0.

[**Implementing ATAG 2.0**](http://www.w3.org/TR/IMPLEMENTING-ATAG20/)
is a supporting informative document that helps readers understand and
use ATAG. Implementing ATAG 2.0 provides the rationale for each
guideline; and for each success criterion, it provides the further
explanation of the intent of the success criteria, examples, and links
to resources.

## ATAG Report Tool

The [**ATAG Report Tool**](https://www.w3.org/WAI/atag/report-tool/) helps evaluators report on the accessibility of authoring tools. It guides you through the ATAG requirements, lets you record your evaluation results for each requirement, and generates a report of the authoring tool's ATAG conformance.

## ATAG Versions: 1.0 and 2.0

ATAG 2.0 is a W3C Recommendation. This means that ATAG 2.0 is a
completed standard, having received public comments, completed
implementation testing, demonstrated real world examples of products
that are using ATAG 2.0 to make their products more accessible, and
being approved by the W3C membership. (These stages are explained in
[How WAI Develops Accessibility Guidelines through the W3C
Process](http://www.w3.org/WAI/intro/w3c-process).)

[Authoring Tool Accessibility Guidelines
1.0](http://www.w3.org/TR/2000/REC-ATAG10-20000203/) was approved in
February 2000. While ATAG 1.0 is still a valid standard, it is outdated.
ATAG 2.0 is the current standard.

## Translations

ATAG 2.0 is available as an Authorized W3C Translation in Chinese, Simplified: [无障碍创作工具指南(ATAG) 2.0](https://www.w3.org/Translations/ATAG20-zh/).

## Who develops ATAG

ATAG was developed by the Authoring Tool Accessibility Guidelines
Working Group ([ATAG WG](http://www.w3.org/WAI/AU/)), which is part of
the World Wide Web Consortium ([W3C](http://www.w3.org/)) Web
Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). For more
information about the working group, see the [AUWG
page](http://www.w3.org/WAI/AU/).

[How WAI Develops Accessibility Guidelines through the W3C Process:
Milestones and Opportunities to
Contribute](http://www.w3.org/WAI/intro/w3c-process) describes formal
periods for public review. Opportunities for review and comment of WAI
documents are announced on the [WAI home page](http://www.w3.org/WAI/)
and [WAI Interest Group](http://www.w3.org/WAI/IG/) mailing list. An
email address for sending comments is included in the "Status of this
Document" section.

Opportunities for contributing to ATAG and other WAI work are introduced
in [Participating in WAI](http://www.w3.org/WAI/participation).
