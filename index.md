---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}


{: .note } 
Midterm on 5/11/2023 in class 


Click the 📺 icons below to view lecture recording. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
