---
title: Meaningful page titles
description: Pages should have titles that describe what they're about
date: 2022-03-02
---

Good page titles help with orientation and can be really useful for users of adaptive technology. 

Every page we create should have a 'title tag' within its code. 

They can tell a user's screen reading software which page they are on whenever they highlight its tab in their browser. 

`<title>Title of the page</title>`
## The problem

An audit found that the title tags used in the Apply to become an academy service were the same for every page. 

To make matters worse, what they said wasn't helpful. 

![The current text shown in a browser tab.](/images/a2become/PageTitles/current_copy.JPG "An image of the service's current title text shown in a browser tab. It reads 'A2C - GOV.UK'")

### Action required
- Each of the service's title tags should be updated so that they meaningfully describe what the page is about.
  
## Our solution
We wanted to be consistent with what our colleagues in the other teams have done - presenting the page name followed by the name of the service.

> Other SDD services use pages titles like 'Home - Manage an academy transfer'.

### What we wanted to do
We hoped that we could use a script to take the main heading from each page, combine it with the name of the service and replace the existing text in the tag with the result. 

Unfortunately, many of our headings were not descriptive and would make poor page titles. 


### What we decided to do
Fixing all of the existing page headings would need to be done as part of bigger service redesign. So instead we chose to draw up a list of temporary replacement tags for each page. 

Not all of the page headings and title tags would match, but the service would be easier to navigate with screen reading technology.


![We decided to draw up a list of replacement titles.](/images/a2become/PageTitles/title_copy.JPG "A screen grab of a spreadsheet showing a list of page titles and URLs")

### Why we chose this approach

This approach was time consuming but we felt it was the only option, given:

- this was an accessibility issue that needed to be resolved quickly
- any alteration to a page's heading would be a waste of time if the page was later removed or reworked as part of ongoing design changes

 ## Link to prototype

<a href="https://escorci-apply2become.herokuapp.com/privacy" target="_blank">See an updated title in a browser tab (opens in a new tab)</a>


Username: apply </br>
Password: 2become

 <br>
<a class="govuk-link" href="/a2b-external/"> < Go back to design histories</a>