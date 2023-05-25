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


{: .challenge } 
Venky from Amazon's Alexa AI team will be visiting on Thursday 5/25. There will be a 2% extra credit opportunity during his visit.

{: .challenge } 
One more extra credit opportunity: 90%+ CAPE response rate for class yields 0.5% collective boost to final score. 


Click the 📺 icons below to view lecture recording. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
