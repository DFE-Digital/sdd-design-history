---
tags: posts
layout: collection
title: Post-advisory board (AT and A2B)
description: A service to help trusts understand what changes they need to make an application for, and for SDD Delivery Officers to manage those applications.
pagination:
  data: collections.post-advisory-board
  reverse: true
  size: 25
permalink: "post-advisory-board/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 5
---