---
layout: default
title: Services & Rates
class: rates
---

Pricing page

<ul>
{% for item in site.data.pricing %}
<li>{{ item.name }} - {{ item.price }}</li>
{% endfor %}
</ul>