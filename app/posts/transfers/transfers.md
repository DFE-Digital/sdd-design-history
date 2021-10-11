---
tags: posts
layout: collection
title: Manage an academy transfer
description: An internal service for DfE colleagues to manage Academy transfers from one trust to another.
permalink: "transfers/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---

### This project was developed for the SDD at the Department for Education to:

* Create a Proof of Concept (PoC) demonstrating how lightweight front ends scoping the “changing a school’s trust” journey can have enhanced user experience and productivity whilst been able to manipulate data from the existing TRAMS system.

### Our goal was 

To explore if there are any other technological options that would enable SDD to;

* Better serve our users needs
* Address significant accessibility issues identified with the current approach
* Allow us to adapt our service quickly following user feedback, in a cost effective way

As of January 2021, the [Academy transfers prototype](https://academy-transfers-prototype.london.cloudapps.digital) includes more than 17 different pages exploring how we can allow RDD agents to interact with real dynamics 365 data held in TRAMS.


## Iterations

### [Discovery Prototype](academy-transfers-prototype/)

### [Experimenting with Variants](variants/)

### [Choosing a starting page](choosing/)

### [Adopting a projects overview style](project/)
