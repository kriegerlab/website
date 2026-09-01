---
title: Contact
nav:
  order: 5
  tooltip: Email and location
---

# Contact

Our group is based at the Institute of Pathology at Charité – Universitätsmedizin Berlin, Campus Mitte, on the university hospital site and in close proximity to a wide range of neighbouring research institutes; we greatly benefit from the core facilities and other resources available here. 

{%
  include button.html
  type="email"
  text="Email"
  link="teresa.krieger@charite.de"
%}
{%
  include button.html
  type="address"
  text="Address"
  tooltip="Our location on Google Maps"
  link="https://maps.app.goo.gl/JBJioDntUMBHWM6B6"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
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
