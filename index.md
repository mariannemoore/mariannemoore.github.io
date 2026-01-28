---
layout: default
title: Home
class: home
description: "Marianne Moore is a luxury makeup artist specializing in bridal makeup that is tailored to the modern bride. She also offers makeup lessons and artist coaching."
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
img-1="/assets/home/home-1.jpg"
img-2="/assets/home/home-2.jpg"
img-3="/assets/home/home-3.jpg"
alt-1="Bridal makeup by Marianne Moore"
alt-2="Editorial makeup look by Marianne Moore"
alt-3="Makeup artistry by Marianne Moore, Victoria BC"
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

{% include home/testimonial-block.html testimonial=4 %}

{%
include
image-grid.html
type="flat"
img-1="/assets/home/home-4.jpg"
img-2="/assets/home/home-5.jpg"
img-3="/assets/home/home-6.jpg"
alt-1="Luxury makeup application by Marianne Moore"
alt-2="Natural bridal makeup look"
alt-3="Professional makeup artist Victoria BC"
%}