---
layout: collection
title: Post advisory board
description: Documenting the joint work carried out by the transfers and conversion teams on post advisory board discovery.
pagination:
  data: collections.postAB
  reverse: true
  size: 50
permalink: "postAB/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - posts
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 5
---

## How we conduted the discovery work for post-advisory board from AT and A2B landscape

The post-advisory board discovery work is split into two parts:

* Part 1 - focusses on synthesising the existing research to create 'as is' user journeys and identifying the pain points for delivery officers
* Part 2 - will focus on understanding the busness needs from teams within RDD