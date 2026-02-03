---
layout: default
title: Personal Shopping
class: personal-shopping
description: "Personal shopping with Marianne Moore. Get professional guidance and colour matching at Sephora to find the perfect makeup and skincare products for you."
---

<script type="application/ld+json">
{
    "@context": "https://schema.org",
    "@type": "FAQPage",
    "mainEntity": [
        {
            "@type": "Question",
            "name": "How much does a personal shopping session cost?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "A personal shopping session with Marianne Moore is $200 CAD for 90 minutes. You'll receive professional guidance on choosing every product you need, with colour matching done in store to ensure perfect results."
            }
        },
        {
            "@type": "Question",
            "name": "What is included in a personal shopping session?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "Marianne will guide you through every product choice, from skincare through to brushes and tools, discovering the correct makeup textures and colour matches as you go. You'll walk away with curated products selected specifically for you and your lifestyle."
            }
        },
        {
            "@type": "Question",
            "name": "Where does the personal shopping session take place?",
            "acceptedAnswer": {
                "@type": "Answer",
                "text": "Personal shopping sessions take place at your nearest Sephora location, where Marianne will provide personalized guidance and colour matching in store."
            }
        }
    ]
}
</script>

{%
include content-block.html
subheading=page.title
h1=site.data.pages.personal-shopping.callout-1
content=site.data.pages.personal-shopping.content-1
buttonURL="https://mariannemakeup.hbportal.co/public/686db25db26a80001fc14487"
buttonTitle="Book a personal shopping session"
buttonLabel="Book a Session"
%}

<section class="full-width-block lessons">
    <div class="wrapper">
        <div class="content-width">
            <h2>Book Your Session</h2>
            <div class="full-width-block-content">
                <div class="lesson-card-1">
                    <div class="lesson-card-inner">
                        <h3>{{ site.data.pages.personal-shopping.service.title }}</h3>
                        <p class="lesson-price">{{ site.data.pages.personal-shopping.service.price }}</p>
                        <p class="lesson-time">{{ site.data.pages.personal-shopping.service.time }}</p>
                        <p>{{ site.data.pages.personal-shopping.service.content }}</p>
                        {%
                            include button.html
                            href=site.data.pages.personal-shopping.service.url
                            title="Book a personal shopping session with Marianne"
                            label="Book Now"
                            type="secondary"
                        %}
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

{%
include content-block.html
h2=site.data.pages.personal-shopping.callout-2
content=site.data.pages.personal-shopping.content-2
%}
