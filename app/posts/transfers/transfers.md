---
tags: posts
layout: page
title: Manage an academy transfer
description: An internal service to help DfE delivery leads to Manage an academy transfer from one trust to an other.
permalink: "transfers/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 3
---

## Project vision

Make it easy and efficient as possible to successfully transfer an academy to a new trust, where it will thrive

## The problem we are trying to solve

The process to transfer an academy from one trust to an other is currently complex, time consuming, variable and unclear.

## Our hypothesis

Designing and developing a service for RDD delivery officers to manage the process of transferring an academy from one trust to an other using TRAMS api and GDS front-end will make the process easier and accessible to our users.


## Iterations

* [Discovery Prototype](academy-transfers-prototype/)
* [Experimenting with Variants](variants/)
* [Choosing a starting page](choosing/)
* [Adopting a projects overview style](project/)

## Private Beta changes
* [Set transfer dates](set-transfer-dates/)
