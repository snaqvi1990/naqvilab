---
---

{% 
  include section.html
  data-size="full"
  dark=True
%}

## Research
{:.center}

{% include figure.html image="images/main_fig_draft_wcell_short_nobar_rot_facegut.png" width="95%"%}

We seek to understand the quantitative control of gene expression in development and the resulting "tipping points" in disease, knowledge that can lead to more precise, controlled therapies for a range of rare and common disorders.     
<br>
 To achieve these goals, we combine functional genomics and computational modeling using stem cell-derived _in vitro_ models of development. A common theme across projects is the use of highly quantitative tools and approaches: "analog genomics". 
{:.center}


{%
  include button.html
  link="research"
  text="Learn more"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Team
{:.center}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{%
  include button.html
  link="blog"
  text="Join us!"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Key publications
{:.center}

{% include citation.html lookup="doi:10.1101/2024.05.28.596078" style="basic" %}

{% include citation.html lookup="doi:10.1038/s41588-023-01366-2" style="basic" %}

{% include citation.html lookup="doi:10.1038/s41588-021-00827-w" style="basic" %}

{% include citation.html lookup="doi:10.7554/eLife.58615" style="basic" %}

{% include citation.html lookup="doi:10.1126/science.aaw7317" style="basic" %}

{%
  include button.html
  link="publications"
  text="Full publication list"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% include section.html %}

## Affiliations
{:.center}

{% capture col1 %}

{%
  include figure.html
  image="images/bch.png"
  link="https://www.childrenshospital.org/"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/hms_teaching.png"
  link="https://hms.harvard.edu/"
%}

{% capture col3 %}

{%
  include figure.html
  image="images/broad.png"
  link="https://broadinstitute.org/"
%}

{% endcapture %}
{% include cols.html col1=col1 col2=col2 col3=col3 %}
{% include section.html %}


