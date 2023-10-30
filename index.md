---
---

# <font size="-0.001">Quantitative principles of gene regulation in development and disease</font>
{:.center}

{% 
  include section.html
  data-size="full"
%}

## Research
{:.center}

{% capture text %}

The molecular machinery that controls transcription - when and to what extent genes are turned on - is critical for cellular identity and development. Quantitative perturbations to this transcriptional machinery are a frequent cause of both rare, developmental disorders and common variation in trait and disease risk.


{%
  include button.html
  link="research"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
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
{:.center}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Key publications
{:.center}

{% include citation.html lookup="doi:10.1038/s41588-023-01366-2" style="basic" %}

{% include citation.html lookup="doi:10.1038/s41588-021-00827-w" style="basic" %}

{% include citation.html lookup="doi:10.7554/eLife.58615" style="basic" %}

{% include citation.html lookup="doi:10.1126/science.aaw7317" style="basic" %}

{% include citation.html lookup="doi:10.1101/gr.230433.117" style="basic" %}

{%
  include button.html
  link="publications"
  text="Full publication list"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Support
{:.center}

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
{:.center}

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

