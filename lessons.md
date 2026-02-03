---
layout: default
title: Lessons
class: lessons
description: "Professional makeup lessons in Victoria BC with Marianne Moore. Personalized beauty routine refreshes and bridal makeup lessons tailored to your skin type and style."
---

<script type="application/ld+json">
{
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
        {
            "@type": "Question",
            "name": "How much do makeup lessons cost?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "A Beauty Routine Refresh lesson is $350 CAD for 2 hours. A Bridal Makeup Lesson is $400 CAD for 2.5 hours. Both include personalized instruction tailored to your skin type and style."
            }
        },
        {
            "@type": "Question",
            "name": "What is included in a makeup lesson?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "You'll receive a customized beauty routine, personalized application techniques, product recommendations, tips for increasing product longevity, and guidance on which tones work best with your skin type. You're welcome to video your session for future reference."
            }
        },
        {
            "@type": "Question",
            "name": "Who are makeup lessons for?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "Lessons are for anyone looking to refresh their beauty routine, learn new techniques, or get expert guidance on skincare and makeup. The Bridal Makeup Lesson is specifically designed for brides who want to do their own wedding makeup."
            }
        }
    ]
}
</script>

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
    <img src="/assets/lessons/lessons.jpg" alt="Makeup lessons with Marianne Moore in Victoria BC" loading="lazy" width="1024" height="848" style="width: 100%; height: auto;">
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