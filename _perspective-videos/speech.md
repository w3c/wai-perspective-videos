---
title: Text to Speech
order: 4
footer: >
  <p><strong>Status:</strong> Updated 15 September 2016. <br><strong>Editor and project lead:</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Developed by the <a href="https://www.w3.org/WAI/EO/">Education and Outreach Working Group (EOWG)</a> with support from the <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a>, co-funded by the European Commission. <a href="../acknowledgements/">Acknowledgements</a>.</p>
---

Web accessibility is essential for people with disabilities and useful
for all. Learn about the impact of accessibility and the benefits for
everyone in a variety of situations.

## Video on Text to Speech
{:#film.no-display}

{% include video-player.html
    yt-id="8Rn5pXCdZWU"
    yt-id-ad="F3A1VffiOH4"
    captions="speech-en.vtt|en|Captions"
    captions-ad="speech_ad-en.vtt|en|Captions"
    descriptions=""
    descriptions-ad="speech_ad_desc-en.vtt|en|Descriptions"
%}

What is "Text to Speech"? {#what}
-------------------------

Many computers and mobile devices today have built in text-to-speech
software. Some people with disabilities, including people who are blind,
use specialized software called screen readers. Screen readers provide
important functionality such as navigating through headings, speaking
image alternatives, and identifying internal and external links. They
can also highlight the text as it is being read aloud for people to see
and hear the content at the same time. Content must be coded properly so
that all of the functionality of the text-to-speech software works with
the content.

Who depends on this feature? {#who}
----------------------------

-   People who are blind and cannot see what is on the screen.
-   People who have partial sight (often legally blind) and cannot see
    certain types of content.
-   People with dyslexia and other cognitive and learning disabilities
    who need to hear and see the text to better understand it.

What are the additional benefits? {#others}
---------------------------------

-   Content can be read aloud for people who cannot read the written
    language.
-   Content can be read aloud for people who prefer to listen, for
    example, while multi-tasking.

What needs to happen for this to work? {#action}
--------------------------------------

Use semantic HTML markup for structures such as headings, paragraphs,
lists, forms, and tables. Provide text alternatives for images, icons,
and other non-text content. Ensure [keyboard
compatibility]({{ "/perspective-videos/keyboard/" | relative_url }}), and ensure that text information is
understandable without the visual context.

Learn more {#resources}
----------

-   **Accessibility Principle:**
    -   [Text alternatives for non-text
        content]({{ "/fundamentals/accessibility-principles/" | relative_url }}#alternatives)
    -   [Content can be presented in different
        ways]({{ "/fundamentals/accessibility-principles/" | relative_url }}#adaptable)
-   **Getting Started:**
    -   [Write meaningful text alternatives for
        images]({{ "/tips/writing/" | relative_url }}#write-meaningful-text-alternatives-for-images)
    -   [Use headings to convey meaning and
        structure]({{ "/tips/writing/" | relative_url }}#use-headings-to-convey-meaning-and-structure)
    -   [Identify page language and language
        changes]({{ "/tips/developing/" | relative_url }}#identify-page-language-and-language-changes)
-   **Easy Check:**
    -   [Image text alternatives ("alt
        text")]({{ "/test-evaluate/preliminary/" | relative_url }}#images)
    -   [Basic Structure
        Check]({{ "/test-evaluate/preliminary/" | relative_url }}#structure)
-   **User Story:**
    -   [Ms. Laitinen, Accountant with
        blindness]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
    -   [Ms. Kaseem, Teenager with
        deaf-blindness]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)
    -   [Ms. Olsen, Classroom student with attention deficit
        hyperactivity disorder (ADHD) and
        dyslexia]({{ "/people-use-web/user-stories/" | relative_url }}#classroomstudent)
-   **Web Content Accessibility Guidelines ([WCAG
    Overview]({{ "/standards-guidelines/wcag/" | relative_url }})):**
    -   [Success Criteria relating to "images" and
        "structure"](https://www.w3.org/WAI/WCAG20/quickref/?tags=images%2Cstructure)
-   **Mobile Applicability:**
    -   [Non-text objects (images, sound, video) with no text
        alternative]({{ "/standards-guidelines/shared-experiences/" | relative_url }}#non-text)
    -   [Information conveyed only using CSS (visual
        formatting)]({{ "/standards-guidelines/shared-experiences/" | relative_url }}#visual-formatting)
    -   [Non-descriptive link
        label]({{ "/standards-guidelines/shared-experiences/" | relative_url }}#link-label)
-   **Tutorial:**
    -   [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/)
        (several related topics)

