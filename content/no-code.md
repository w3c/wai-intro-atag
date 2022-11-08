---
# NEW: Comments for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/

# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "[Draft] Guidelines to Make Your No-code website Tool Accessible"
# title_html: "[Draft] Guidelines to Make your no-code website Tool Accessible<br>Get the gist of what your tool needs to support accessible website creation"
nav_title: "@@ no-code"

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
  path: content/no-code.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /standards-guidelines/atag/no-code/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr
layout: default

# NEW: 3 navigation lines below are only needed for multi-page resources where you have previous and next at the bottom. If so, un-comment them; otherwise delete these lines.
# navigation:
  # previous: /path/to/previous/file/
  # next: /path/to/next/file/
# @@SLH To Do: figure out if need to add lang here, too, and if this replaces "order" from older resources?

ref: /standards-guidelines/atag/no-code/   # Translators, do not change this
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

This page introduces a standard to help you make your no-code website tool accessible to people with disabilities.

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

Your current customers and potential new customers need no-code website tools that:

* are accessible to users with disabilities
* produce accessible content

In many situations, accessibility is required by law and is a procurement requirement.

## Examples

### Everyone Can Add Blocks of Content

<p class="persona"><strong>Persona: </strong>
 Mohamed is a blind cook. He uses a screen reader to manage his restaurant’s website.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I want to add a new block of content to my home page. The documentation of my tool says I need to drag and drop, but I cannot do that as I do not use the mouse. I tried using my screen reader’s built-in functionality to drag and drop, but still it does not work.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I can use the keyboard to select the block of content I want to use and then put it wherever I want on the page.
      </q></span></p>
    </li>
  </ul>
</div>

Users who have auditory, cognitive, neurological, physical, speech, and visual disabilities need to be able to add, customize,and remove blocks of content.

### Everyone Can Produce Accessible Content

<p class="persona"><strong>Persona: </strong>
  Amahle is a hairdresser.
</p>

<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        My clients say they cannot book an appointment because my website has accessibility issues. The tool I am using does not have anything to improve the accessibility of my website.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        The tool suggests me to add headings, lists, and labels. My clients say it is very accessible.
      </q></span></p>
    </li>
  </ul>
</div>

Your users may not be able to fix accessibility issues. Your tool needs to support them when creating content so that the output is accessible. This includes making headings, paragraphs, lists, labels, and other content structures accessible.

### Everyone Can Create Accessible Multimedia Content

<p class="persona"><strong>Persona: </strong>
  Dacso runs a mechanics shop.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I want everybody to enjoy the videos of my mechanics shop. But I have no idea how to do it.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        Whenever I upload a video, my tool advices me to add captions and suggests me to add transcript or descriptions for everybody to enjoy my videos.
      </q></span></p>
    </li>
  </ul>
</div>

Your users may not have the knowledge and/or resources to create accessible multimedia content for people who cannot see and hear well or at all. Your tool needs to support the addition of alternatives for audio and video content so that people with disabilities can enjoy them.

## The Accessibility Standard to Help You

Your no-code tool is sometimes called an "authoring tool". It can enable users to create accessible websites and multimedia content.

There is an international standard to help you meet accessibility needs: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Initiative ([WAI](/WAI/)).

Use ATAG to help make your tool:

* accessible to website creators [Part A]
* support accessible content for website consumers [Part B]

ATAG covers the example personas above:

* **Everyone can add blocks of content**: [TBD]
* **Everyone can produce accessible content**: [TBD] 
* **Everyone can create accessible multimedia content**: [TBD]

And ATAG covers much more.

To get started putting ATAG to work for you, see:

* [[ATAG Overview]](/standards-guidelines/atag/), with links to the ATAG standard and implementing ATAG
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/), a paraphrased summary to give you an idea of what's covered in ATAG

