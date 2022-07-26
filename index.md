---
title: Philippa Kavanagh - English Classes
layout: home
description: Jekyll Serif contains content types for a typical business website. The theme is fully responsive, blazing fast and artfully illustrated.
intro_image: "images/illustrations/sincerely-media-dGxOgeXAXm8-unsplash.jpg"
intro_image_absolute: false
intro_image_hide_on_mobile: true
show_call_box: true
bodyClass: page-about
---

{% for lang in site.languages %}
    {% if lang == site.active_lang %}
{{ lang }}
    {% else %}
        {% if lang == site.default_lang %}
<a href=" {{ page.url }}">{{ lang }}</a>
        {% else %}
<a href="/{{ lang }}{{ page.url }}">{{ lang }}</a>
        {% endif %}
    {% endif %}
{% endfor %}

# Pip Kavanagh - English Classes

Individual and small-group English classes. Friendly, open and professional teaching style for levels A1 - C2.

## Why choose me?


1) Personalised, dynamic and varied classes

2) Native English speaker

3) [Cambridge University graduate](/about/) with teaching accreditations

4) 10 + years teaching experience 

5) Cambridge, IELTS, APTIS exam preparation experience 

6) Central Santander location (or in your home)

7) Comfortable, friendly environment

8) [Competitive prices](/prices/) with discounts for advanced payments 

9) Flexible timetable 

10) [Amazing results](/testimonials/)  