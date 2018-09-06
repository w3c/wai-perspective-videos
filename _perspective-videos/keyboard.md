---
title: Keyboard Compatibility
order: 1
description: Short video about keyboard compatibility for web accessibility - what is it, who depends on it, and what needs to happen to make it work.
image: /perspective-videos/img/keyboard.jpg
footer: >
  <p><strong>Status:</strong> Updated 15 September 2016. <br><strong>Editor and project lead:</strong> <a href="https://www.w3.org/People/shadi">Shadi Abou-Zahra</a>. Developed by the <a href="https://www.w3.org/WAI/EO/">Education and Outreach Working Group (EOWG)</a> with support from the <a href="https://www.w3.org/WAI/DEV/">WAI-DEV project</a>, co-funded by the European Commission. <a href="../acknowledgements/">Acknowledgements</a>.</p>
---

Web accessibility is essential for people with disabilities and useful
for all. Learn about the impact of accessibility and the benefits for
everyone in a variety of situations.

## Video on Keyboard Compatibility
{:#film.no-display}

{% include video-player.html
    yt-id="93UgG72os8M"
    yt-id-ad="1rBwxGMT9ZM"
    captions="/perspective-videos/cc/keyboard-en.vtt|en|Captions"
    captions-ad="/perspective-videos/cc/keyboard_ad-en.vtt|en|Captions"
    descriptions="/perspective-videos/cc/"
    descriptions-ad="/perspective-videos/cc/keyboard_ad_desc-en.vtt|en|Descriptions"
%}

## What is "Keyboard Compatibility"?
{:#what}

All functionality must be usable with the keyboard. That is, users can access and move between links, buttons, forms, and other controls using the Tab key and other keystrokes. Websites should not require a mouse; for example, pop-up calendars should also let users type in a date.

## Who depends on this feature?
{:#who}

-   People with physical disabilities who cannot use the mouse.
-   People who are blind, and cannot see the mouse pointer on the screen.
-   People with chronic conditions, such as repetitive stress injuries (RSI), who should limit or avoid use of a mouse.

## What are the additional benefits?
{:#others}

-   Content works for people with temporary limitations, such as a broken arm or broken mouse.

## What needs to happen for this to work?
{:#action}

Native HTML controls, like links, buttons, and form elements, work with the keyboard by default and should be used where possible. Custom-made controls, CSS styles, and scripts that control interaction may need additional coding for keyboard compatibility. Ensure that the tab order is logical, to allow keyboard navigation around the content and controls. Provide a way for users to jump between blocks of content and controls. Keyboard issues occur particularly in forms, menus, and applications with many controls.

## Learn more
{:#resources}

-   **Accessibility Principle:**
    -   [Functionality is available from a
        keyboard]({{ "/fundamentals/accessibility-principles/" | relative_url }}#keyboard)
-   **Getting Started:**
    -   [Ensure that all interactive elements are keyboard
        accessible]({{ "/tips/developing/" | relative_url }}#ensure-that-all-interactive-elements-are-keyboard-accessible)
-   **Easy Check:**
    -   [Keyboard access and visual focus]({{ "/test-evaluate/preliminary/" | relative_url }}#interaction)
-   **User Story:**
    -   [Mr. Jones, Reporter with repetitive stress
        injury]({{ "/people-use-web/user-stories/" | relative_url }}#reporter)
    -   [Ms. Laitinen, Accountant with
        blindness]({{ "/people-use-web/user-stories/" | relative_url }}#accountant)
    -   [Ms. Kaseem, Teenager with
        deaf-blindness]({{ "/people-use-web/user-stories/" | relative_url }}#teenager)
-   **Web Content Accessibility Guidelines ([WCAG
    Overview]({{ "/standards-guidelines/wcag/" | relative_url }})):**
    -   [Success Criteria relating to
        "keyboard"](https://www.w3.org/WAI/WCAG20/quickref/?tags=keyboard)
-   **Mobile Applicability:**
    -   [Mouse required for interaction and
        navigation]({{ "/standards-guidelines/shared-experiences/" | relative_url }}#mouse)
-   **Tutorial:**
    -   [Web Accessibility Tutorials](https://www.w3.org/WAI/tutorials/)
        (several related topics)
