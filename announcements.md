---
layout: page
nav_order: 1
title: Nástěnka
nav_exclude: false
description: Oznámení a jiná sdělení týkající se výuky.
---

# Nástěnka

Aktuální informace ke změnám ve výuce a jiné volatilní informace.

{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
