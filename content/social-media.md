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

class: tight-page

inline_css: |
  .quotes {margin-bottom: 0;}
  .quotes ul {list-style-type: none;}
  .quotes li>p {display:table-row;}
  .quotes li>p span {display:table-cell;}
  .persona {font-style: italic;}
  .issue {font-style: italic; display:table-cell; width: 6em;}
  q:before {content: open-quote;color: #005a6a;font-style: italic;}
  q:after {content: close-quote;color: #005a6a;font-style: italic;}

---

{::nomarkdown}
{% include box.html type="start" h="2" title="Summary" class="full" %}
{:/}

This page briefly introduces a standard to help you make your social media platform accessible to creators and users with disabilities.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::options toc_levels="2" /}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}
{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Why Accessibility Matters

People with disabilities use your social media tool for work, leisure, and others.

By making your social media tool accessible, you are helping create more inclusive communities and you are improving your tool's reputation.

Content creators and content consumers need social media that:

* is accessible to users with disabilities
* can produce accessible content

**Accessibility is required by law and is a procurement requirement** in many situations.

## Example Scenarios

The persona scenarios below are examples of accessibility issues with social media platforms.

### Everyone Can Rely on your Tool

<p><span class="persona">Persona: </span>
 Banele is a social media consultant with low vision. She relies on magnification software to increase the font size of the tools she uses.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I used to be able to read through and publish client messages using our social media platform and my magnification software. Unfortunately, after the last update, I can't get to the publish button when  my magnification software is enabled.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        The tool is overall very accessible. The last update even included some new accessibility features.
      </q></span></p>
    </li>
  </ul>
</div>

Users who have auditory, cognitive, neurological, physical, speech, and visual disabilities often rely on robust platforms which work with the assistive technology they use. You need to ensure accessibility is preserved when updating your tool's user interface or functionality.

### Everyone can Read and Process Content at Their Own Pace

<p><span class="persona">Persona: </span>
  Nushi is an influencer with reading disabilities. He uses tools to have text read aloud.
  </p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        When content refreshes too fast, I have problems keeping up-to-date. It is difficult for me to manage new comments.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I can decide when to have new content appear. This way I can read at my own pace, use tools to read content aloud if needed, and make sure I am reacting and responding to my followers when I need to. 
      </q></span></p>
    </li>
  </ul>
</div>

People who use social media have different abilities. For example, they may read content at different paces. Your tool should allow them to decide how they want to process the new content that appears.

### The Tool Supports the Creation of Accessible Social Experiences

<p><span class="persona">Persona: </span>
  Enhamed manages the social media profile of a small business. He has just started thinking about the accessibility of the content he uploads.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I get complaints from customers that our links, images and videos are not accessible.  I can't do anything about it because my tool does not allow me to add these features.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I can add alt text for my images, show captions for my videos, and write custom text for my links.
      </q></span></p>
    </li>
  </ul>
</div>

People who upload different types of content need tools that can create accessible social experiences. This includes adding alternatives to images and multimedia and using a clear link text that explains what the link is about.

## The Accessibility Standard to Help You

Your social media tool is sometimes called an "authoring tool" because people use it to share content with their family, friends, colleagues, and followers. There is an international standard that addresses accessibility needs in social media tools: Authoring Tool Accessibility Guidelines (ATAG).

**Use ATAG to help make your tool**:

* **accessible to content creators (Part A)**
* **support accessible content for content consumers (Part B)**

{::nomarkdown}
{% include box.html type="start" title="Examples" class="simple aside" %}
{:/}

ATAG covers the example scenarios above:

* _Everyone Can Rely on your Tool_ &mdash; ATAG says: conforming to WCAG 2.0, following existing platform accessibility guidelines, and implementing communication with platform accessibility services facilitates access by all authors, including those using assistive technologies.
* _Everyone can Process Content at Their Own Pace_ &mdash;ATAG says: Some authors who have difficulty typing, operating the mouse, or processing information can be prevented from using systems with short time limits or that require fast reaction speeds.
* _The Tool supports the creation of accessible social experiences_ &mdash; ATAG says: When accessibility checking is an integrated function of the authoring tool, it helps make authors aware of web content accessibility problems (WCAG) during the authoring process, so they can be immediately addressed.

And ATAG covers much more.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

**To get started putting ATAG to work for you, see**:

* **[[ATAG Overview]](/standards-guidelines/atag/)**, with links to the ATAG standard and Implementing ATAG
* **[[ATAG at a Glance]](/standards-guidelines/atag/glance/)**, a paraphrased summary to give you an idea of what's covered in ATAG