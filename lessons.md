---
layout: default
title: Lessons
class: lessons
---

{%
include content-block.html
subheading=page.title
h1=site.data.pages.lessons.first-callout
content=site.data.pages.lessons.content-1
buttonURL="/contact/"
buttonTitle="Get in touch with Marianne"
buttonLabel="Book a Lesson"
%}

<section class="content-width">
    <img src="/assets/lessons/9C9A6024.jpg" style="width: 100%; height: auto;">
</section>

{%
include content-block.html
content=site.data.pages.lessons.content-2
%}

{% include lessons/lesson-options.html %}