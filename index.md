---
layout: default
title: Home
class: home
---

{%
include content-block.html
h1=site.data.pages.home.first-callout
buttonURL="/bridal/"
buttonTitle="Learn more about my bridal process"
buttonLabel="Bridal Services"
%}

{%
include
image-grid.html
img-1="/assets/home/9C9A7892.jpg"
img-2="/assets/home/9C9A8410.jpg"
img-3="/assets/home/9C9A6058.jpg"
%}

{%
include content-block.html
h2="It’s nice to meet you"
content=site.data.pages.home.content-block-1
buttonURL="/bridal/"
buttonTitle="Learn more about my bridal process"
buttonLabel="Bridal Services"
%}

{% include divider.html %}

{% include home/testimonial-block.html %}