---
layout: default
title: Home
class: home
---

{% include home/hero.html %}

{% include home/blurb.html %}

{% include home/intro.html %}

<script>
    document.addEventListener("DOMContentLoaded", function() {
        /* 
        Get named elements
        */
        const name = document.getElementById('name');
        const subtitle = document.getElementById('subtitle');
        /*
        Add necessary event listeners
        */
        window.addEventListener('scroll', () => {
            /*
            Handles offsetting horizontally
            */
            let offsetForHorizontalMovement = window.scrollY / 5;           
            name.style.transform = `translateX(${-offsetForHorizontalMovement}px)`;
            subtitle.style.transform = `translateX(${offsetForHorizontalMovement}px)`;
            /*
            Handles opacity transition
            */
            let offsetForOpacity = window.scrollY / 300;
            let opacity = 1 - offsetForOpacity;
            name.style.opacity = opacity;
            subtitle.style.opacity = opacity;
        });
    });
</script>