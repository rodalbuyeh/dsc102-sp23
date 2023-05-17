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

{: .important}
PA1 extra credit bounty: <=100 seconds

{: .challenge } 
Jules from Anyscale will be visiting on Thursday 5/18, and Venky from Amazon's Alexa AI team will be visiting on Thursday 5/25. There will be 2% extra credit opportunities available during each of those classes (4% total), in-person attendance is strongly encouraged.  

{: .revision } 
The prompt for PA2 has been re-uploaded to this page on May 17th to account for DSMLP changes. Please re-download if you have an earlier version. We have also revised the slides for 5/16 to clarify notation as mentioned during lecture. 


Click the 📺 icons below to view lecture recording. 



<!-- [Jump to the current week](#week-03){: .btn } -->

{% for module in site.modules %}
{{ module }}
{% endfor %}
