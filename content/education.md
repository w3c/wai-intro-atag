---
# NEW: Comments for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/

# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "[Draft] Guidelines to Make Your LMS Accessible"
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

inline_css: |
  blockquote {font-style: normal !important;}
  blockquote p:first-of-type:before, blockquote p:last-of-type:after, blockquote dl:last-of-type:after {content: '' !important;margin-left: 0 !important;}
  blockquote.sc {padding: 0 10px 15px 20px;border: solid #ccc 1px;background: #f0f0f0;color: #000; margin: 0;}
  .quotes {margin-bottom: 0;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row;}
  .quotes li>p span {display:table-cell;}
  .issue {font-weight: bold; display:table-cell; width: 6em;}
  q:before {content: open-quote;color: #005a6a;font-weight: bold;}
  q:after {content: close-quote;color: #005a6a;font-weight: bold;}

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces a standard to help you make your learning management system (LMS) and other authoring tools for instructors accessible to people with disabilities.

It includes quotes from personas (fictional users of your tool) to help you understand some aspects of accessibility for your tools.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2,3" /}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}
{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Introduction [Why does Accessibility Apply to LMS Developers?]

Learning management systems (LMS) allow professors, lecturers, and other instructors to develop training materials. They have responsibility for their content to be accessible. The tool they use to produce their content can help or hinder their ability to create accessible content.

If you develop or maintain an LMS, you can help your users by making your tool:

* accessible to authors with disabilities, and
* capable of producing accessible content.

## Examples

### Make your Tool Accessible for Users with Disabilities

<p class="persona"><strong>Persona: </strong>Lisa is a physics professor at a large university. She is blind and uses a screen reader that reads aloud the information on her screen.</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>Some LMSs don't enable me to create accessible materials. Their built-in editor does not work with my screen reader. I cannot preview the contents within the tool.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>Other LMSs enable me to create accessible resource materials and assignments. I can preview the results all within the tool. I can also track students progress and grade their assignments. The tool works well with my screen reader.</q></span></p>
    </li>
  </ul>
</div>

The tool itself should be accessible to instructors who have auditory, cognitive, neurological, physical, speech, and visual disabilities. Users with disabilities need to be able to use your tool to do everything that users without disabilities do.

### Support Alternatives to Images and Multimedia

<p class="persona"><strong>Persona: </strong>John is a high school history teacher. He has low vision and uses screen magnifier software.</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>Some LMSs don't support the inclusion of alternatives to images and multimedia. I have a hard time when I need to include them. I need third-party software to make them available for my students.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>Other LMSs suggest the inclusion of alternatives, such as description, transcripts, and captions, for the images and multimedia content that I use in my courses</q></span></p>
    </li>
  </ul>
</div>

people may not see/hear well or at all. They need alternatives to images and multimedia content, such as description, captions, and transcripts. When your tool supports the inclusion of these alternatives, it helps authors make multimedia content more accessible.

### Ensure your Tool Produces Accessible Content

<p class="persona"><strong>Persona: </strong>Ivan is a linguistics lecturer with autism.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>Some LMSs don't guide me to fix existing accessibility issues of my courses. It is very difficult to fix these problems when I use them.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>Other LMSs guide me to fix potential accessibility issues. Creating accessible content is much easier when I use one of those.</q></span></p>
    </li>
  </ul>
</div>

Your tool needs to be able to produce accessible content. This includes:

* ensuring any automatically-generated content is accessible
* helping authors fix potential accessibility issues.

Accessible LMS make it easier for content authors to create accessible content.

### Promote accessibility features

<p class="persona"><strong>Persona: </strong>Jenny is an online English teacher with attention deficit. She is new to accessibility.</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>Some LMSs don't document their accessibility features. It is hard to pick one or the other when I need to deliver accessible materials.</q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>Other LMSs are very well documented for accessibility. I have been able to get started very easily.</q></span></p>
    </li>
  </ul>
</div>

Promote the accessibility features of your tool. For example, you can document how to produce accessible content. When your tool actively promotes the creation of accessible content, it helps those who are new to accessibility as well as it encourages authors to create accessible content.

## Accessibility standard for LMSs and other authoring tools

There is an international standard to help you meet accessibility user needs for learning management systems (LMS) and other authoring tools: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Initiative ([WAI](/WAI/)).

ATAG covers the above examples:

* Make your Tool Accessible for Users with Disabilities &mdash; Make the authoring tool user interface accessible
* Support alternatives to images and multimedia &mdash; Assist authors with managing alternative content for non-text content
* Ensure your tool produces accessible content &mdash; Authors are supported in producing accessible content
* Promote accessibility features &mdash; Authoring tools promote and integrate their accessibility features

Use ATAG to make your tool:

* work well for people with disabilities
* support the creation of accessible content

Learn more from:

* [[ATAG Overview]](/standards-guidelines/atag/) &mdash; Introduces the standard
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/) &mdash; Is a paraphrased summary
* [ATAG 2.0 standard](https://www.w3.org/tr/atag) &mdash; Is the standard itself
* [Implementing ATAG 2.0 document=(https://www.w3.org/TR/IMPLEMENTING-ATAG20/) &mdash; Provides guidance on how to implement ATAG]
