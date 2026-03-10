---
layout: default
title: About
class: about
description: "Meet Marianne Moore, a professional bridal makeup artist with over 17 years of global experience, including MAC Cosmetics and London Fashion Week. Based in Victoria BC."
---

{%
include content-block.html
subheading=page.title
h1=site.data.pages.about.callout-1
content=site.data.pages.about.content-1
%}

{%
include
image-grid.html
type="flat"
img-1="/assets/about/about-1.jpg"
img-2="/assets/about/about-2.jpg"
img-3="/assets/about/about-3.jpg"
alt-1="Marianne Moore, bridal makeup artist"
alt-2="Marianne Moore applying makeup"
alt-3="Marianne Moore, Victoria BC makeup artist"
%}

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

{% include divider.html %}

<div class="podcast-feature">
    <a href="https://open.spotify.com/episode/5vuVU3ShPakUFCrmLUcEHj?si=ec0ef93799dd4308" class="podcast-link" target="_blank" rel="noopener noreferrer">
        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" clip-rule="evenodd" d="M12 0C5.37 0 0 5.37 0 12s5.37 12 12 12 12-5.37 12-12S18.63 0 12 0Zm5.5 17.31c-.22.36-.69.47-1.05.25-2.87-1.76-6.49-2.16-10.75-1.18-.41.09-.82-.16-.91-.57-.09-.41.16-.82.57-.91 4.66-1.07 8.67-.61 11.89 1.36.36.22.47.69.25 1.05Zm1.47-3.26c-.28.44-.87.58-1.31.3-3.29-2.02-8.3-2.61-12.19-1.43-.5.15-1.03-.14-1.18-.64-.15-.5.14-1.03.64-1.18 4.44-1.35 9.96-.69 13.74 1.63.44.28.58.87.3 1.32Zm.13-3.39C15.24 8.4 8.8 8.18 5.12 9.27c-.6.18-1.23-.16-1.41-.76-.18-.6.16-1.23.76-1.41 4.24-1.28 11.3-1.04 15.74 1.63.54.32.72 1.02.4 1.56-.32.54-1.02.72-1.56.4l-.05-.03Z"/></svg>
        More of my story on this podcast episode
    </a>
</div>