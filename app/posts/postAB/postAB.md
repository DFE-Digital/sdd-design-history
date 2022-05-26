---
layout: collection
title: Post advisory board
description: An internal service helping DfE Delivery Officers convert a school to an academy, transfer an academy from one Trust to another, or make a change to an academy after the proposal has been approved by the Regional Director.
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


