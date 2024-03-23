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

{% include section.html background="images/background.jpg" dark=true %}

At GraPharma, we're not just a team; we're a vibrant community of young, passionate individuals driven by a shared love for science and innovation. Our youthful energy fuels our creativity and propels us forward as we explore the frontiers of pharmaceutical research.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/1-team.jpg" %}
{% include figure.html image="images/2-team.jpg" %}
{% include figure.html image="images/1-logo.png" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
