---
tags: posts
layout: collection
title: Concerns Casework
description: An internal service for DfE colleagues to manage trusts with pending concerns.
permalink: "concerns/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    url: "https://concerns-casework-design-history.netlify.app/"
    permalink: false
    parent: home
---
