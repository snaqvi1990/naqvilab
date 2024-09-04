---
title: Team
nav:
  order: 3
  tooltip: About our team
---

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



