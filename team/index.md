---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Faculty
{% include list.html data="members" component="portrait" filters="role: full-prof" %}
{% include list.html data="members" component="portrait" filters="role: assoc-prof" %}
{% include list.html data="members" component="portrait" filters="role: assis-prof" %}

## PhD
{% include list.html data="members" component="portrait" filters="role: phd" %}

## Masters
{% include list.html data="members" component="portrait" filters="role: masters" %}

## Undergraduate
{% include list.html data="members" component="portrait" filters="role: undergrad" %}

{% include section.html background="images/background.jpeg" dark=true %}
