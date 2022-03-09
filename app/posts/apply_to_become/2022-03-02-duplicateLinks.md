---
title: Accessibility issue 08 - Duplicate links 
description: Duplicate links create overload of information and confusion for people who use screen readers. 
date: 2022-03-02
---
## Description
Screen reader assistive technologies can accurately interpret and analyse content if it is entered correctly from the outset.  Errors such as duplicate link descriptions can cause confusion to users as they offer no context to the where the link will direct them to.
There is also an issue with the design of the page since it doesn’t follow any of the GDS approved components. The current design creates an overload of information to the user since they will have to review all answers before if they want to change anything from the list. 

---

> Image 1. Shows a preview of a page with information about the conversion. There are multiple links and they all read _Change your answers_

![Image 1: screenshot of a list with information about the conversion](/images/a2become/links/01-links.jpg "Image 1: screenshot of a list with information about the conversion")

---

> Image 2. Shows a preview of what a screen reader will read out to users. The multiple links do not give any indication regarding which change is being applied.

![Image 2: screenshot of screen reader links repeating information](/images/a2become/links/02-links.png "Image 2: screenshot of screen reader links repeating information")

---

## Action Required 
- Redesign the page using the [GDS summary list](https://design-system.service.gov.uk/components/summary-list/) component 
- Use the full description of the link when coding the page 

---

## Proposed solution
> Image 3. Shows the new proposed design for this page

![Image 3: screenshot of the proposed new design using 3 columns and individual change links"](/images/a2become/links/03-links.png "Image 3: screenshot of the proposed new design using 3 columns and individual change links")

---

> Image 4. Shows the link list with the correct description when using a screen reader

![Image 4: screenshot of screen reader links with proper description](/images/a2become/links/04-links.png "Image 4: screenshot of screen reader links with proper description")

## Link to prototype
See this component in action
[Prototype: Summary list](https://escorci-apply2become.herokuapp.com/about) 
Username: apply
Password: 2become



<br><br>
<div class="app-back-to-top app-back-to-top--hidden" data-module="app-back-to-top">
  <a class="govuk-link govuk-link--no-visited-state app-back-to-top__link" href="#top">
    <svg role="presentation" focusable="false" class="app-back-to-top__icon" xmlns="http://www.w3.org/2000/svg" width="13" height="10" viewBox="0 0 13 17">
      <path fill="currentColor" d="M6.5 0L0 6.5 1.4 8l4-4v12.7h2V4l4.3 4L13 6.4z"></path>
    </svg> Back to top
  </a>
</div>

<br>
<a class="govuk-link" href="/a2b-external/"> < Go back to design histories</a>