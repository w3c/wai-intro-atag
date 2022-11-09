---
# NEW: repos for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/
# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "[Draft] Guidelines to Make Your Social Media Platform Accessible"
nav_title: "@@ Social Media"

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
  path: content/social-media.md    # Add the language shortcode to the middle of the filename, for example: content/index.fr.md
permalink: /standards-guidelines/atag/social-media/   # Add the language shortcode to the end, with no slash at end, for example: /link/to/page/fr
layout: default

# NEW: 3 navigation lines below are only needed for multi-page resources where you have previous and next at the bottom. If so, un-comment them; otherwise delete these lines.
# navigation:
  # previous: /path/to/previous/file/
  # next: /path/to/next/file/
# @@SLH To Do: figure out if need to add lang here, too, and if this replaces "order" from older resources?

ref: /standards-guidelines/atag/social-media/   # Translators, do not change this
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

This page introduces a standard to help you make your social media platform accessible to people with disabilities.

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

Your current customers and potential new customers need social media platforms  that:

* are accessible to users with disabilities
* produce accessible content

In many situations, accessibility is required by law and is a procurement requirement.

## Examples

### Everyone CanRely on your Tool

<p class="persona"><strong>Persona: </strong>
 Banele is a blind community manager. She uses a screen reader that reads aloud the information on her screen.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I used to be able to manage my client’s social media profile. The  tool updated and broke most of the accessibility features. I am no longer able to do my job.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        The tool keeps being accessible update after update. If something ever breaks, I can go back to the previous version of the tool where it worked as expected.
      </q></span></p>
    </li>
  </ul>
</div>

Users who have auditory, cognitive, neurological, physical, speech, and visual disabilities often rely on your tool to do their job. You need to ensure accessibility is preserved when updating your tool's user interface or functionality.

### Everyone can Process Content at Their Own Pace

<p class="persona"><strong>Persona: </strong>
  Nushi is a journalisst with low vision. She uses magnification software to increase the font size.
  </p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I can't read the content in this tool. It updates so quickly that I cannot follow through.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I can decide when the tool refreshes for new content. This way I can read at my own pace when content updates are very fast.
      </q></span></p>
    </li>
  </ul>
</div>

people who interact with social platforms have different abilities. Some need to read content at a different pace. Your tool should allow them to decide how they want to process the new content that appears.

### Everyone can Create Accessible Social Experiences

<p class="persona"><strong>Persona: </strong>
  Enhamed is a journalist. He is an authoritative source in his community, but has no idea about accessibility.
</p></
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I get complaints that links, images, and videos that I upload are not accessible. I can't do anything about it, my tool does not allow me to change anything in them.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        When I add a link, I can change its texts so that it is clear what the link is about. when I upload images and videos, the tool suggests me to add alternative texts, captions, and descriptions as appropriate.
      </q></span></p>
    </li>
  </ul>
</div>

People who post to social media need to be able to create accessible social experiences. This includes using a clear link text that explains what the link is about, as well as adding alternatives to images and multimedia.

## The Accessibility Standard to Help You

Your social media platform is an "authoring tool". It can enable users to create accessible social experiences.

There is an international standard to help you meet accessibility needs: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Initiative ([WAI](/WAI/)).

Use ATAG to help make your tool:

* accessible to content creators (Part A)
* support accessible content for content consumers (Part B)

ATAG covers the above examples:

* Everyone Can Rely on your Tool [TBD]
* Everyone can Process Content at Their Own Pace [TBD]
* Everyone can Create Accessible Social Experiences [TBD]

To get started putting ATAG to work for you, see:

* [[ATAG Overview]](/standards-guidelines/atag/), with links to the ATAG standard and implementing ATAG
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/), a paraphrased summary to give you an idea of what's covered in ATAG

