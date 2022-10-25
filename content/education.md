---
# NEW: Comments for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/

# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "Accessible Tooling for Education"
title_html: "Accessible Tooling for Education<br>Get the gist of what your tool needs to support accessible education"
nav_title: "Education"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2022111@-30   # Put the date of this translation YYYY-MM-DD (with month in the middle)

# translators:    # remove from the beginning of this line and the lines below: "# " (the hash sign and the space)
# - name: "Jan Doe"   # Replace Jan Doe with translator name
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple translators
# contributors:
# - name: "Jan Doe"   # Replace Jan Doe with contributor name, or delete this line if none
# - name: "Jan Doe"   # Replace Jan Doe with name, or delete this line if not multiple contributors

github:
  repository: w3c/wai-intro-atag
  path: content/education.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /standards-guidelines/atag/education/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr

# NEW: 3 navigation lines below are only needed for multi-page resources where you have previous and next at the bottom. If so, un-comment them; otherwise delete these lines.
# navigation:
  # previous: /path/to/previous/file/
  # next: /path/to/next/file/
# @@SLH To Do: figure out if need to add lang here, too, and if this replaces "order" from older resources?

ref: /standards-guidelines/atag/education/   # Translators, do not change this
changelog: /@@/changelog/
acknowledgements: /@@/acknowledgements/  # NEW: delete if don"t have a separate acknowledgements page. And delete it in the footer below.
license: creative-commons   # NEW: delete if not creative-commons

description:  # NEW: add a 150ish-character-description for social media   # translate the description
image: /content-images/wai-@@repo/social.png  # NEW: image for social media

# NEW: Footer below has several options, and not all will be relevant for specific pages. (Ask Shawn if questions.)

# In the footer below:
# Do not translate or change CHANGELOG or ACKNOWLEDGEMENTS.
# Translate the other words below, including "Date:" and "Editor:"
# Translate the Working Group name. Leave the Working Group acronym in English.
# Do not change the dates in the footer below.
footer: >
   <p><strong>Date:</strong> Updated @@ Month 2021. First published Month 20@@. CHANGELOG.</p>
   <p><strong>Editors:</strong> @@name, @@name. Contributors: @@name, @@name, and <a href="https://www.w3.org/groups/wg/@@wg/participants">participants of the @@WG</a>. ACKNOWLEDGEMENTS lists contributors and credits.</p>
   <p>Developed by the @@ Working Group (<a href="http://www.w3.org/WAI/@@/">@@WG</a>). Developed as part of the <a href="https://www.w3.org/WAI/@@/">WAI-@@ project</a>, @@co-funded by the European Commission.</p>

---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page helps you realize why Authoring Tool Accessibility Guidelines (ATAG) applies to your authoring tool.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction

"The LMS I use at the university allows me to create materials for my courses, as well as grade assignments from my students."

W3C/WAI's Authoring Tool Accessibility Guidelines (ATAG) explains how to:

* make authoring tools themselves accessible, and
* support the creation of content that conforms to the Web Content Accessibility Guidelines (WCAG)

For more info, see [[Authoring Tool Accessibility Guidelines (ATAG) Overview]](/standards-guidelines/atag/).

Ilya is a senior instructor. She is blind, and uses her computer with a screen reader. Authoring tools can help or hinder Ilya  when creating accessible content. For more info on what ATAG contains, see [[ATAG at a glance]](/standards-guidelines/atag/glance)

The list below contains some of the ways for you to meet ATAG. This way, Ilya can create accessible training using your tool. For the whole list of requirements under ATAG, see [Authoring Tool Accessibility Guidelines (ATAG) 2.0 document](https://www.w3.org/TR/ATAG/)

---

## Draft ideas

### Support Different Ways of Content Presentation

Some groups of users with disabilities need to customize the font type and/or size. Others may need to tweak  spacing between sections, paragraphs, and words. Ensure your tool enables users to customize font types, sizes, and spacing.

### Support Inclusion and Presentation of Alternatives

Some people cannot see images and video well or at all. Others cannot hear audio well or at all. Ensure your tool support content authors to provide the necessary alternatives for images, audio, and video. This alternatives include captions, transcript, description, and sign language interpretation.

### Ability to Define Reading Order

The reading order specifies how content should be read and processed. This may be apparent visually, but it also needs to be communicated to assistive technologies. Ensure your tool supports content authors when specifying the reading order.

### Support for Navigation and Content Identification

Users rely on a variety of methods for navigating and identifying content. These include tables of contents, regions, links, and headings.

Ensure your tool supports content authors to specify these methods. For example, every unit may be presented on a separate page for users to more easily locate it. Different sections within the unit may have accessible headings to facilitate navigation and identification of the different content sections.

### Communicate Students Progress

Ensure students are aware of their progress through the training. This includes information about the current lesson, how many lessons they have completed, and how many lessons remain.

###  Ability to complete quizzes, submit assignments 

Ensure your tool supports students when  submitting quizzes, completing assignments, and any other assessment.

