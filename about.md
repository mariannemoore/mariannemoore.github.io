---
layout: default
title: About
class: about
---

{% include page-intro.html title=page.title callout=site.data.pages.about.first-callout %}

{% include about/headshot.html %}

{% include content-block.html content=site.data.pages.about.content-block-1 %}

{% include button.html href="/contact/" label="Inquire" %}

{% include content-block.html content=site.data.pages.about.content-block-2 %}