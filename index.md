---
layout: default
title: Home
class: home
---

{% include home/hero.html %}

{% include callout.html content=site.data.pages.home.callout-1 %}

{% include content-block.html content=site.data.pages.home.intro %}

{% include home/cta.html %}

{% include home/image-grid.html %}

{% include content-block.html content=site.data.pages.home.block-1 %}

{% include home/headshot.html %}

{% include home/cta.html %}

<script>
    document.addEventListener("DOMContentLoaded", function() {
        const marqueeTop = document.getElementById('marquee-top');
        const marqueeBottom = document.getElementById('marquee-bottom');

        window.addEventListener('scroll', () => {
            let offsetForHorizontalMovement = window.scrollY / 5;
            marqueeTop.style.transform = `translateX(${-offsetForHorizontalMovement}px)`;
            marqueeBottom.style.transform = `translateX(${offsetForHorizontalMovement}px)`;
        });
    });
</script>