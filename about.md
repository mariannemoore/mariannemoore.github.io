---
layout: default
title: About
class: about
---

{%
include content-block.html
subheading=page.title
h1=site.data.pages.about.callout-1
content=site.data.pages.about.content-1
%}

{% include about/headshot.html %}

{%
include content-block.html
h2=site.data.pages.about.callout-2
content=site.data.pages.about.content-2
buttonURL="/contact/"
buttonTitle="Get in touch with Marianne"
buttonLabel="Inquire"
%}

{% include divider.html %}

{% include about/testimonial-block.html testimonial=3 %}