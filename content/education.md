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
  .sc dt {
    display: list-item;
    list-style-type: disc;
    float: left;
    font-weight: bold;
    margin-left: 2em;
    margin-right: 1ex;
    margin-top: 0;
  }
  .sc dt:after {
    content: ":";
  }
  /* new start */	
  .sc dl dd {margin: 0 0 0.5em 2em;}
  .sc dd {margin-left: 0;}
  .sc dd {display: block;  margin-inline-start: 40px;}
  /* new end */	
  .sc p:last-of-type {margin-bottom: 1em}
  .sc p:last-child, .sc *:last-child {margin-bottom: 0}
  .sclabel {
    padding: 0;
    margin: 0;
    color: #686868;
  }
  div.note, div.ednote, div.warning {
      margin-top: 1em;
      margin-bottom: 1em;
  }
  .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
    .note > p:first-child, .ednote > p:first-child,.warning > p:first-child { margin-top: 0 }
  .note, .ednote, .warning {
      padding: .5em;
      border-left-width: 1px;
      border-left-style: solid;
  }
  div.note , div.ednote,  div.warning {
      padding: 1em 1.2em 0.5em;
      margin: 1em 0;
      position: relative;
      clear: both;
  }
  span.note, span.ednote, span.warning { padding: .1em .5em .15em; }
  .note, .ednote {
      border-color: #52e052;
  }
  .note-p {margin-top: 0}
  #markdown-toc ul li {
    margin-bottom: 0;
  }

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page introduces a standard to help you make your learning management system (LMS) and other authoring tools for instructors accessible to people with disabilites.

It includes quotes from personas (fictional people) to help you understand some aspects of accessibility for your tools.

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

### Make your tool accessible for users with disabilities

<p class="persona">Ilsa is a physics professor at a large university. She is blind and uses a screen reader that reads aloud the information on her screen.</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Some LMSs don't... </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>Other LMSs ...</q></span></p>
    </li>
  </ul>
</div>

@@previous draft: I am a blind instructor. With my screen reader, I can use the LMS to create accessible resource materials and assignments. I can preview the results all within the tool. I can also track students progress and grade their assignments. The tool works well with my screen reader.

The tool itself should be accessible to instructors who have auditory, cognitive, neurological, physical, speech, and visual disabilies. Users with disabilities needs to be able to use your tool to do everyting that users without disabilities do.

### Support alternatives to images and multimedia

<p class="persona">@@ persona intro</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Some LMSs don't... </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>Other LMSs ...</q></span></p>
    </li>
  </ul>
</div>

@@previous draft: I am a professor who uses screen magnifier software. When I need to use images and multimedia content in my courses, the LMS suggests the inclusion of alternatives, such as description, transcripts, and captions.

people may not see/hear well or at all. They need alternatives to images and multimedia content, such as description, captions, and transcripts. When your tool supports the inclusion of these alternatives, it helps authors make multimedia content more accessible.

### Ensure your tool produces accessible content

<p class="persona">@@ persona intro</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Some LMSs don't... </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>Other LMSs ...</q></span></p>
    </li>
  </ul>
</div>

@@previous draft: I am a lecturer with autism. I use a tool that generates accessible content for my students. When there is a potential accessibility issue, the tool guides me to fix it.

Your tool needs to be able to produce accessible content. This includes:

* ensuring any automatically-generated content is accessible
* helping authors fix potential accessibility issues.

Accessible LMS make it easier for content authors to create accessible content.

### Promote accessibility features

<p class="persona">@@ persona intro</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem:</span><span><q>Some LMSs don't... </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well:</span><span><q>Other LMSs ...</q></span></p>
    </li>
  </ul>
</div>

@@previous draft: I am an trainer. I have been asked to create an accessible course, but I am new to accessibility. Fortunately, the tool is very well documented for accessibility and I have been able to get started very easily.

Promote the accessibility features of your tool. For example, you can document how to produce accessible content. When your tool actively promotes the creation of accessible content, it helps those who are new to accessibility as well as it encourages authors to create accessible content.

## Accessibility standard for LMSs and other authoring tools

There is an international standards to help you meet accessibility user needs for learning management systsmes (LMS) and other authoring tools: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Iniative ([WAI](@@link)).

ATAG covers the above examples:
* @@wording from above &mdash; @@wording from ATAG
* @@wording from above &mdash; @@wording from ATAG
* ...

Use ATAG to make your tool:

* work well for people with disabilities
* support the creation of accessible content

Learn more from:

* [[ATAG Overview]](/standards-guidelines/atag/)
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/) is a paraphrased summary
* [ATAG 2.0 standard](https://www.w3.org/tr/atag) is the standard itself
* @@ implementing
