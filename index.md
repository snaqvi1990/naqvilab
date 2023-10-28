---
---

# Quantitative principles of gene regulation in development and disease

An engaging 1-3 sentence description of your lab.

{% 
  include section.html
  size=full
%}

## Research

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

{% include section.html %}

## Team

{% include section.html %}

## Key publications

{% include citation.html lookup="doi:10.1038/s41588-023-01366-2" style="basic" %}

{% include citation.html lookup="doi:10.1146/annurev-genom-120121-102607" style="basic" %}

{% include citation.html lookup="doi:10.1038/s41588-021-00827-w" style="basic" %}

{% include citation.html lookup="doi:10.1101/2020.04.20.051631" style="basic" %}

{% include citation.html lookup="doi:10.1126/science.aaw7317" style="basic" %}

{% include citation.html lookup="doi:10.1101/gr.230433.117" style="basic" %}

{% include section.html %}

## Support
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/bch.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/nidcr.png"
%}

{% endcapture %}
{% include cols.html col1=col1 col2=col2 %}

## Affiliations
{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/bch.png"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/hms_teaching.png"
%}

{% endcapture %}
{% include cols.html col1=col1 col2=col2 %}

