---
layout: collection
title: Manage an academy transfer
description: An internal service to help DfE delivery leads to Manage an academy transfer from one trust to an other.
pagination:
  data: collections.transfers
  reverse: true
  size: 50
permalink: "transfers/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - posts
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---
