---
title: First post
description: Our first design based on user needs, our findings from private beta and implementation of GDS patterns.
date: 2021-02-12
parent: Academy Conversions

related:
  items:
  - text: User needs
    href: /conversions/user_needs
  - text: Glossary
    href: /conversions/glossary

---

### Date the work was done

January 2021

## Introduction

The end to end Apply to become an Academy service will manage the whole journey for a school converting to an academy, from the initial application through to the point at which the academy opens. In June 2020 we released the ‘Apply to become an Academy’ digital application service on GOV.UK.
This project focuses on the internal service, the service that will support DfE delivery officers mange the project from application, through Headteacher Board to academy opening.

## The internal service

The internal service has been built using Microsoft Dynamics and had been in Private Beta for some time. Usability testing was conducted on an initial working product this testing followed the progress of several users through the process. The research concluded that there were a number of issues with the service, the most impactful included:

- Delivery officers [users] felt unable to use the service to produce the documents for Headteacher Board due to problems they experienced.
- Some of the key navigational and workflow issues experienced during private beta were also evidenced during alpha. Although changes had been implemented to help solve these issues before launching beta, they were not sufficient to overcome the problems.

To address the issues encountered with the private beta system a technical investigation, which was completed at the end of January by another team, determined that the best approach for this service would be to use the GDS design kit to create a bespoke user interface. This would allow users to interact with an accessible and consistent UI.

## Design

Our first prototype is a static Figma clickthrough. It is an interpretation of the teamwork done to collate user needs, as well as findings from private beta and the implementation of the GDS design kit. The prototype was used to help the team understand gaps in knowledge and as a conversational aid with users to help us fill some of those gaps.

{% from "screenshots/macro.njk" import appScreenshots with context %}
{{ appScreenshots({
  items: [ {
      text: "Projects list - with tabs and filters",
      img: { src: "1_V1-PAGE-filter-AllA2B.png" }
    },  {
      text: "Projects list - with tabs and filters selected",
      img: { src: "2_V1-PAGE-filter-HTB.png" }
    }, {
      text: "Projects list - with double filters",
      img: { src: "3_V1-PAGE-filter-All.png" }
    }, {
      text: "Task list - new",
      img: { src: "4_V1-PAGE-tasklist-1.png" }
    }, {
      text: "Task - set HTB date",
      img: { src: "5_V1-PAGE-SetHTBdate-1.png" }
    }, {
      text: "Task - review HTB date details",
      img: { src: "6_V1-PAGE-SetHTBdate-3.png" }
    }, {
      text: "Task - viability and risks",
      img: { src: "7_V1-PAGE-Viability-3.png" }
    }, {
      text: "Task - review viability and risks details",
      img: { src: "8_V1-PAGE-Viability-4.png" }
    }, {
      text: "Task list - with task complete",
      img: { src: "9_V1-PAGE-task list-HTB.png" }
    }, {
      text: "Generating HTB templates",
      img: { src: "11_V1- PAGE-Create HTB.png" }
    }, {
      text: "Review HTB template",
      img: { src: "12_V1-PAGE-Review HTB template1.png" }
    }, {
      text: "Review - select reviewer",
      img: { src: "14_V1-PAGE-Review-1.png" }
    }, {
      text: "Review - check details",
      img: { src: "13_V1-PAGE-Review-Summary1.png" }
    }, {
      text: "Review -success screen",
      img: { src: "15_V1-PAGE-Review-1.png" }
    }, {
      text: "Send documents to secretariat - check details",
      img: { src: "16_Frame 7.png" }
    }, {
      text: "Send documents to secretariat - success",
      img: { src: "17_V1-PAGE-Review-1.png" }
    }]
}) }}
