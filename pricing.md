---
layout: default
title: Pricing
class: pricing
---

{%
include content-block.html
subheading=page.title
h1=site.data.pages.pricing.callout-1
content=site.data.pages.pricing.content-1
%}

{% include pricing/pricing-bridal.html %}

{% include pricing/pricing-bride-only.html %}

<section class="solo-image content-width">
    <img src="/assets/pricing/pricing.jpg" style="width: 100%; height: auto;">
</section>

{% include pricing/pricing-general.html %}

{% include pricing/testimonial-block.html testimonial=1 %}

{% include pricing/pricing-additional.html %}