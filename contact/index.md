---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="grapharm.ml@gmail.com"
  link="grapharm.ml@gmail.com"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/contactus-1.jpg"
  caption=" "
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/contactus-2.jpg"
  caption=" "
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}


