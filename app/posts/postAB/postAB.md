---
layout: collection
title: Post advisory board
description: Documenting the work done in the post-AB part of the process.
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
    order: 6
---


