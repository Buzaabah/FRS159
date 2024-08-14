---
layout: page
title: Schedule
description: Listing of course modules and topics
nav_order: 3
---

# Schedule

{: .note}
>
> We will stick to this schedule, and should there be any important changes to the schedule, assignments, or reading materials, you'll receive an email notification.
>

{% for module in site.modules %}
  {{ module }}
  {% if module.title == "Week 6 - Distant Reading" %}
> 🌴 **Spring Break** 🌴  
>
> Enjoy a well-deserved break!
{: .notice--spring-break }
  {% endif %}
{% endfor %}
