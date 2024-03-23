---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Whether you're a researcher, industry professional, or enthusiast, we welcome the opportunity to connect with you. Drop us a message, give us a call, or connect with us on social media. We look forward to hearing from you and exploring how we can collaborate to advance the field of pharmaceutical research together.

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


