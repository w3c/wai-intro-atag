---
# NEW: Comments for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/

# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "[Draft] Education"
# title_html: "[Draft] Accessible Tooling for Education<br>Get the gist of what your tool needs to support accessible education"
nav_title: "Education"

lang: en   # Change "en" to the translated-language shortcode from https://www.iana.org/assignments/language-subtag-registry/language-subtag-registry
last_updated: 2022-10-25   # Put the date of this translation YYYY-MM-DD (with month in the middle)

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
layout: default

# NEW: 3 navigation lines below are only needed for multi-page resources where you have previous and next at the bottom. If so, un-comment them; otherwise delete these lines.
# navigation:
  # previous: /path/to/previous/file/
  # next: /path/to/next/file/
# @@SLH To Do: figure out if need to add lang here, too, and if this replaces "order" from older resources?

ref: /standards-guidelines/atag/education/   # Translators, do not change this
# changelog: /@@/changelog/ 
# acknowledgements: /@@/acknowledgements/  # NEW: delete if don"t have a separate acknowledgements page. And delete it in the footer below.
license: creative-commons   # NEW: delete if not creative-commons

description:  # NEW: add a 150ish-character-description for social media   # translate the description
# image: /content-images/wai-@@repo/social.png  # NEW: image for social media

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

## Why does Accessibility Apply to LMS Developers?

A Learning Management System (LMS) allows professors, lecturers, and other instructors to author training materials. Authors have responsibility for their content to be accessible. But the tool they use to produce their content can help or hinder their ability to create accessible content.

If you develop or maintain an LMS, you can help your users by making your tool:

* work well for people with diabilities
* support the creation of accessible content
* 

## Make your Tool Accessible

> I am a blind instructor. With my screen reader, I can use the LMS to create accessible resource materials and assignments. I can preview the results all within the tool. I can also track students progress and grade their assignments. The tool works well with my screen reader.

The tool itself should be accessible. That means people with disabilities should be able to use it, just like people without disabilities do.

## Support Alternatives to Images and Multimedia

> I am a professor who uses screen magnifier software. When I need to use images and multimedia content in my courses, the LMS suggests the inclusion of alternatives, such as description, transcripts, and captions.

people may not see/hear well or at all. They need alternatives to images and multimedia content, such as description, captions, and transcripts. When your tool supports the inclusion of these alternatives, it helps authors make multimedia content more accessible.

## Ensure your Tool can Produce Accessible Content

> I am a lecturer with autism. I use a tool that generates accessible content for my students. When there is a potential accessibility issue, the tool guides me to fix it.

Your tool needs to be able to produce accessible content. This includes:

* ensuring any automatically-generated content is accessible
* helping authors fix potential accessibility issues.

Accessible LMS make it easier for content authors to create accessible content.

## Promote Accessibility Features

> I am an trainer. I have been asked to create an accessible course, but I am new to accessibility. Fortunately, the tool is very well documented for accessibility and I have been able to get started very easily.

Promote the accessibility features of your tool. For example, you can document how to produce accessible content. When your tool actively promotes the creation of accessible content, it helps those who are new to accessibility as well as it encourages authors to create accessible content.

## Meet ATAG

By meeting ATAG, you'll make your tool:

* accessible to authors with disabilities, and
* capable of producing accessible content.

To learn more, visit:

* [[Authoring Tool Accessibility Guidelines (ATAG) Overview]](/standards-guidelines/atag/) &mdash; introduces the Authoring Tool Accessibility Guidelines (ATAG) web standard.
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/) &mdash; Provides a paraphrased summary of Authoring Tool Accessibility Guidelines (ATAG) 2.0. 
* [ATAG 2.0 document](https://www.w3.org/tr/atag) &mdash; provides guidelines for designing web content authoring tools that are both more accessible to authors with disabilities and designed to enable, support, and promote the production of more accessible web content by all authors.
