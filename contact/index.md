---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

{% include icon.html icon="fa-regular fa-envelope" %}Contact

{% include button.html type="email" text="jose.rodriguez233@upr.edu" link="jose.rodriguez233@upr.edu" %}
{% include button.html type="phone" text="(787) 764-0000 x.1-88131" link="+1-787-764-0000" %}
{% include button.html type="address" tooltip="Our location on Google Maps for easy navigation" link="https://maps.app.goo.gl/XDqvLNy2Tii8V4KC6" %}

{% include section.html %}

{% capture col1 %}

{% include figure.html image="images/photo.jpg" caption="Department of Biology, UPR Río Piedras" %}

{% endcapture %}

{% capture col2 %}

{% include figure.html image="images/photo.jpg" caption="Natural Sciences Building, San Juan, Puerto Rico" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
**Mailing Address**
Department of Biology
University of Puerto Rico
Río Piedras Campus
PO Box 23360
San Juan, PR 00931-3360
{% endcapture %}

{% capture col2 %}
**Join the Lab**
We recruit motivated undergraduate and graduate students. Please email Dr. Rodríguez-Martínez with your CV and a brief statement of your research interests.
{% endcapture %}

{% capture col3 %}
**Collaborations**
We welcome collaborations with researchers interested in transcription factor biology, non-coding genomics, and cardiovascular disease. Feel free to reach out!
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
