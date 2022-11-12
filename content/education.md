---
# NEW: Comments for new repos start with "NEW". Please delete the NEW comments. Leave the other comments for translators. Also, search for @@s to replace. For multi-page resources and other frontmatter info, see: https://wai-website-theme.netlify.app/writing/frontmatter/

# Translation instructions are after the "#" character in this first section. They are comments that do not show up in the web page. You do not need to translate the instructions after #.
# In this first section, do not translate the words before a colon. For example, do not translate "title:". Do translate the text after "title:".

title: "[Draft] Standards to Make Your LMS Accessible"
nav_title: "@@Education"

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

This page briefly introduces a standard to help make your learning management system (LMS) and other education tools accessible to people with disabilities.

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

Your current customers and potential new customers need learning management systems (LMS) that:

* are accessible to instructors and other LMS users with disabilities
* produce accessible content for students

In many situations, accessibility is required by law and is a procurement requirement.

## Example Scenarios

The persona scenarios below are examples of accessibility issues with LMSs.

### Everyone Can Use Previews

<p class="persona"><strong>Persona: </strong>
 Zola is a physics professor at a large university. She is blind and uses a screen reader that reads aloud the information on her screen.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I can't preview uploaded content using my screen reader. I can't navigate the preview like I can a regular web page.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        The content preview works just like a web page in a browser. I can navigate it easily using my screen reader's functionality.
      </q></span></p>
    </li>
  </ul>
</div>

Users who have auditory, cognitive, neurological, physical, speech, and visual disabilities need to be able to preview the course content.

### Everyone Can Edit Content

<p class="persona"><strong>Persona: </strong>
  Aroon is a school administrator. He is a quadriplegic and uses speech recognition to navigate through applications and websites.
  </p>

<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I can't sort the course attendees data table. There's no way to activate the column sort with voice.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        I can interact with the course attendees table by voice. I can select the column I want to sort by.
      </q></span></p>
    </li>
  </ul>
</div>

Some people cannot use a mouse. They need to be able to use your LMS with their tools, such as speech recognition, keyboard, and switches. 

### The LMS Helps Make Course Content Accessible

<p class="persona"><strong>Persona: </strong>
  Irina is the director of an online professional training center. She is an expert in her job; however, she doesn't know much about accessibility.
</p>
<div class="quotes">
  <ul>
    <li>
      <p><span class="issue">Problem: </span><span><q>
        I'm adding charts to our courses. I have no idea what I need to do to make them accessible to students with disabilities.
      </q></span></p>
    </li>
    <li>
      <p><span class="issue">Works well: </span><span><q>
        Whenever I add a chart to a course, the tool prompts me to add a short description and a full text alternative for the chart data. There's also "Learn More" that explains why it's important for accessibility, and how to do it well.
</q></span></p>
    </li>
  </ul>
</div>

LMSs need to produce accessible content. Part of that is up to your tool and part is up to the user. Your tool can provide prompts and information to help users know what they need to do to provide accessible course content.

## The Accessibility Standard to Help You

Your learning management system (LMS) is sometimes called an "authoring tool" because people use it to author or create course content.

There is an international standard to help you meet accessibility needs: **Authoring Tool Accessibility Guidelines (ATAG)**. ATAG is developed by the W3C Web Accessibility Initiative ([WAI](/WAI/)).

Use ATAG to help make your tool:

* accessible to instructors and other users with disabilities (Part A)
* support accessible content for students (Part B)

ATAG covers the example scenarios above:

* **Everyone can use previews** &mdash; ATAG says: Ensure that previews are accessible. Course authors often periodically check how browsers will display the content to students. Authors with disabilities need the same opportunity to check their work.
* **Everyone can edit content** &mdash; ATAG says: Provide keyboard access to authoring features. Some authors with limited mobility or visual disabilities do not use a mouse. Instead, they require keyboard interface access to all of the functionality of the authoring tool.
* **The LMS helps make course content accessible** &mdash; ATAG says: Guide authors to produce accessible content. Assist authors with managing alternative content for non-text content. Ensure that documentation promotes the production of accessible content.

And ATAG covers much more.

To get started putting ATAG to work for you, see:

* [[ATAG Overview]](/standards-guidelines/atag/), with links to the ATAG standard and Implementing ATAG
* [[ATAG at a Glance]](/standards-guidelines/atag/glance/), a paraphrased summary to give you an idea of what's covered in ATAG
