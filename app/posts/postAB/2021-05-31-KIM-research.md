---
title: Design changes from KIM research
description: We did some research on KIM, part of the existing system that delivery officers use to complete conversion and transfers projects.
date: 2022-05-27
---
### Date the work was done
May 2022

## Knowledge and Information Management (KIM) research
KIM is part of the existing system that Delivery Officers use to complete projects.

It’s a piece of software that holds some of the information that they need to convert a school, transfer or make a change to an academy.

There’s an organisational need for KIM to be made-read only, and ultimately replaced. The work we’re doing will help to make this happen.

As a team, we felt it was important for us to understand how Delivery Officers use KIM. This would help us to know how making these changes to KIM would impact their work and inform our decisions about what content was required within the product we create.

### Key research questions
In this research, we wanted to find answers to the following questions:
- What are the main tasks Operational Delivery Team delivery officers and team leads use KIM for?
- When do they use KIM in the conversion process and how often?
- What do they find useful / not useful about KIM?

### Method
The research sessions would be remote. They would be a one-to-one interview and observation with the researcher and participant, lasting 60 minutes.

- Interview: Understand main tasks
- Observation: See them carry out those tasks
- 3 delivery officers and 1 team lead would take part.

## What we learnt
The research gave us lots of useful insights that informed design decisions.

### What delivery officers use KIM for
We found that delivery officers use KIM to:
- Update fields after regional delivery handover
- Update school details if they change
- Confirm grant payments
- Update document statuses
- Confirm documents are saved, redacted, and sent
- Update general comments throughout

### What’s useful and what’s unhelpful about KIM
The research also told us that:
- KIM adds little value to what delivery officers have to do. They enter data for other people's benefit
- KIM is slow and so delivery officers avoid using it when possible 
- KIM doesn't help delivery officers keep track of their tasks as it doesn't include all the tasks involved
- Many delivery officers create their own docs or systems keep track of where they are up to in a project
- Many delivery officers have created their own way to easily access key information about a project

### Other useful observations
- It can be challenging for delivery officers to keep track of multiple projects at the same time
- Stakeholder details are important, delivery officers use them often
- The last month of a conversion is the busiest
- The project overview list is useful to navigate between projects

### Changes made to the click-through from findings
Following the research, we made changes to the prototype in Figma.
- Different line widths added to the projects list page to distinguish between each month’s projects
- The school’s unique reference number (URN) and school type have been added to main task list, so users can easily identify that they are working on the right project
- To accommodate the new URN the trust name has been moved to the right-hand side of the task list page. This also matches how trust names appear in the earlier stage of the service that the Prepare for advisory board team are working on
- Additional fields have been added to the project information page to ensure we have all the fields delivery officers require.


{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [{
      text: "Projects list",
      img: { src: "KIM-project-list.png" }
    }, {
      text: "Tasklist",
      img: { src: "KIM-task-list.png" }
    }, {
    text: "Projects overview",
      img: { src: "KIM-Project-overview.png" }
      }, {
    text: "First tasks checklist",
      img: { src: "KIM-first-tasks.png" }
    }]
}) }}
