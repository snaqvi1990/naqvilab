---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Starting July 2024, we will be a part of the <a href="https://www.childrenshospital.org/research/divisions/gastroenterology-hepatology-and-nutrition-research">Division of Gastroenterology, Hepatology, and Nutrition</a> at Boston Children's Hospital. The lab will be located on the 8th floor of the Karp Research Building in the <a href="https://campustour.hms.harvard.edu/#UMAP_2014022756162">Longwood Medical Area</a>.

{%
  include button.html
  type="email"
  text="Email Sahin"
  link="sahin.naqvi@childrens.harvard.edu"
%}
{%
  include button.html
  type="phone"
  text="(650) 725-6063"
  link="+1-650-725-6063"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/wxkFGwRoMeBHgn8SA"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/karp.jpeg"
  caption="Karp Research Building"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/longwood.jpeg"
  caption="Longwood Medical Area"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
