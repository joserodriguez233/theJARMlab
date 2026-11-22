---
title: Team
nav:
  order: 4
  tooltip: About our team
---

{% include icon.html icon="fa-solid fa-users" %}Team

The JARMlab is a diverse, interdisciplinary research group at the University of Puerto Rico Río Piedras. We work at the intersection of biophysics, genomics, and cardiovascular biology, and are committed to training the next generation of Puerto Rican scientists through rigorous, inclusive, and impactful science.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

**We are actively recruiting!**
We welcome motivated undergraduate and graduate students who are excited about transcription factor biology, genomics, and computational approaches to disease. If you are interested in joining the lab, please reach out to Dr. Rodríguez-Martínez at [jose.rodriguez233@upr.edu](mailto:jose.rodriguez233@upr.edu) with your CV and a brief statement of your research interests.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
