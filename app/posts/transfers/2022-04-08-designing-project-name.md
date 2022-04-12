---
title: Designing a meaningful way to identify each project
description: We iterated on listing projects by removing the constraint of an incoming and outgoing trust name
date: 2022-04-08
---

We iterated on designing a project name a few times based on the business needs. At first, we used the transferring academy name as the project name. We changed this to the incoming trust name to accommodate the feature of selecting multiple academies into a single transfer project.

Our future roadmap indicated that users will be able to select multiple outgoing trusts in one project, therefore using the outgoing trust name as the project name would not work. We solved this by using the incoming trust name as the project name and decided unofficially that we will work with the policy to limit our service capability to select only one incoming trust per project. There is still work to be done to understand the complex types of transfers. [We mapped out the known complex cases here](https://lucid.app/lucidspark/7533970a-968e-4d7a-ae76-6489d32f9546/edit).

Limiting the product capability to allow the selection of only one incoming trust per project will give our product an advantage of keeping the service simple to use and de-risk any performance related issues.

We also introduced a unique reference number for each of the projects which includes the region of the incoming trust, whether it is a single academy transfer (SAT) or multiple academy transfer (MAT) followed by a sequence of unique numbers generated in the backend.

We tested the revised project name with users and received positive feedback on the reference numbers. Users were able to identify the regional code as well as whether it is a SAT or MAT. We also got feedback to improve on displaying a meaningful way to identify each project.

* Users told us that they would like to see the outgoing trust name and the incoming trust name displayed in the project listing

* Users thought that the project name will be the outgoing trust name as they are used to that in the as-is project templates

With that in mind, we revised the project listing in the below format:

>**Reference number**
>**Outgoing trust:** Outgoing trust name
>**Incoming trust:** Incoming trust name

Screenshot of the revised project listing.
![Screenshot of the revised project listing](/images/transfers/designing-project-name/image-1.png)

## We also carried over the new project name into the tasklist

We replaced the incoming trust name to the project reference number as the h1 in each task list. We also carried over the outgoing and incoming trust name into the task list on the sidebar. We made the assumption that users will find it helpful to access the trust information from [Get information about schools](https://get-information-schools.service.gov.uk/Groups/Group/Details/15751) website and linked the outgoing and incoming trust name to the relevant trust information.

Screenshot of tasklist with revised project name.
![Screenshot of the revised project listing](/images/transfers/designing-project-name/image-2.png)

## Github tag

[Github tag – v1.5](https://github.com/DFE-Digital/sdd-services-prototype/releases/tag/v1.5)