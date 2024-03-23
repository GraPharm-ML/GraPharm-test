---
title: About us
nav:
  order: 1
  tooltip: Published works
---


# {% include icon.html %}Our Mission

At GraPharm, we are propelled by an unwavering dedication to innovation and a collective commitment to unraveling the intricate connections among drugs, diseases, pathways, and targets. Our mission transcends traditional boundaries in drug discovery, seeking to unleash the complete potential of pharmaceutical networks for drug repurposing and beyond.

{% include section.html %}

## Highlighted

{% include section.html %}


{% capture col1 %}

{%
  include figure.html
  image="images/graph_pharmaco-01.gif"
  caption=" "
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/graph_pharmaco-02.gif"
  caption=" "
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
