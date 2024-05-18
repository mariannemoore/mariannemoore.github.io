---
layout: default
title: Home
class: home
---

{% include home/hero.html %}

{% include callout.html content=site.data.pages.home.callout-1 %}

{% include content-block.html content=site.data.pages.home.intro %}

{% include button.html href="/bridal/" label="Bridal Services" %}

{% include home/image-grid.html %}

{% include home/testimonial.html %}

{% include content-block.html content=site.data.pages.home.block-1 %}