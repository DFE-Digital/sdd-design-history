---
layout: collection
title: Apply to become an academy
description: An external application form hosted on GOV.UK for schools applying to become an academy.
pagination:
  data: collections.a2b-external
  reverse: true
  size: 50
permalink: "a2b-external/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - posts
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 5
---
