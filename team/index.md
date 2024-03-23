---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Driven by passion and expertise, our team at GraPharma is committed to pushing the boundaries of AI in pharmaceuticals. Together, we're revolutionizing data analysis and knowledge graph development to empower informed decision-making in the industry.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}



{% endcapture %}

{% include grid.html style="square" content=content %}
