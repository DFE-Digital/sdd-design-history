---
layout: collection
title: Complete conversions, transfers and changes
description: An internal service helping DfE Delivery Officers convert a school to an academy, transfer an academy from one trust to another, or make a change to an academy after the proposal has been approved.
pagination:
  data: collections.complete-conversions-transfers-and-changes
  reverse: true
  size: 50
permalink: "complete-conversions-transfers-and-changes/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - posts
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 6
---


