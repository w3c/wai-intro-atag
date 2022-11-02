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

This page introduces a standard to help you make your learning management system (LMS) and other education  tools accessible to people with disabilities. This includes educators, course administrators, and learning/instructional designers, as well as students and end users.

It includes quotes from personas (fictional users) to help you understand some aspects of accessibility specific to your tools.

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

## Why Accessibility Matters

Your current customers and potential new customers need learning management systems (LMS) that:

* are accessible to instructors with disabilities
* produce accessible content for students

In many situations, accessibility is required by law.

## Examples

### Everyone can Use Previews

<p class="persona"><strong>Persona: </strong>
    Lisa is a physics professor at a large university. She is blind and uses a screen reader that reads aloud the information on her screen.
  </p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I can't preview uploaded content using my screen reader. When I select the preview, I can't navigate it as I regularly do on an HTML page.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        When I select the content preview, I get an HTML view of the content, just as if I were using my browser. I can navigate it easily with my screen reader built-in functionality.
      </q></span></p>
    </li>
  </ul>
</div>

The tool itself should be accessible to instructors who have auditory, cognitive, neurological, physical, speech, and visual disabilities. Users with disabilities need to be able to use your tool to do everything that users without disabilities do.

### Everyone can Edit Content

<p class="persona"><strong>Persona: </strong>
  John is a learning designer. He uses speech recognition software to navigate through systems and websites.
  </p>

<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I can't format my course contents. When I say things like "bold", "italics" or "underlined", nothing happens.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I speak the format I want to use and the contents are updated accordingly.
      </q></span></p>
    </li>
  </ul>
</div>

Users have different ways of interacting with websites, systems, and digital content and might use a range of assistive technologies. When your tool supports this and is set up correctly, it enables users to interact with your LMS successfully. 

### Everyone can Improve Accessibility of Existing Content

<p class="persona"><strong>Persona: </strong>
  Jenny is the director of a rural school.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I want to add some charts in our existing courses but I am not sure how accessible they are for our childrens with disabilities.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        Whenever I add a chart to the course, I get a warning that it may require an alternative text and I get guidance on how to include it.
</q></span></p>
    </li>
  </ul>
</div>

Support the creation of accessible content. This includes ensuring any automatically-generated content is accessible as well as helping authors fix potential accessibility issues.

## The Accessibility Standard to Help You

Your learning management system (LMS) is an "authoring tool". It can enable users to create accessible educational materials.

There is an international standard to help you meet accessibility needs: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Initiative ([WAI](/WAI/)).

Use ATAG to help make your tool:

* accessible to educators and course administrators with disabilities [Part A]
* support accessible content for students [Part B]

ATAG covers the above examples: @@add numbers below.

* Make your Tool Accessible for Users with Disabilities &mdash; "Editing views are perceivable" and "Editing views are operable"
* Support alternatives to images and multimedia &mdash; "Authors are supported in producing accessible content"
* Promote accessibility features and help fix accessibility issues &mdash; "Authoring tools promote and integrate their accessibility features"

To get started putting ATAG to work for you, see:
* [[ATAG Overview]](/standards-guidelines/atag/), with links to the ATAG standard and implementing ATAG
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/), a paraphrased summary to give you an idea of what's covered in ATAG

