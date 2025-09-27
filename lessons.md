---
layout: default
title: Lessons
class: lessons
---

{%
include content-block.html
subheading=page.title
h1=site.data.pages.lessons.callout-1
content=site.data.pages.lessons.content-1
buttonURL="/contact/"
buttonTitle="Get in touch with Marianne"
buttonLabel="Book a Lesson"
%}

<section class="solo-image content-width">
    <img src="/assets/lessons/lessons.jpg" style="width: 100%; height: auto;">
</section>

{%
include content-block.html
h2=site.data.pages.lessons.callout-2
content=site.data.pages.lessons.content-2
%}

{% include divider.html %}

{% include lessons/testimonial-block.html testimonial=0 %}

{% include lessons/lesson-options.html %}

{%
include content-block.html
h2=site.data.pages.lessons.callout-3
content=site.data.pages.lessons.content-3
%}