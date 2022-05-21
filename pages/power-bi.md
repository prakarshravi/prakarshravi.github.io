---
layout: page
show_meta: false
title: "Power BI"
subheadline: "Outcomes"
header:
   image_fullwidth: "leh2.jpg"
permalink: "/power-bi/"
---
<ul>
    {% for post in site.categories.power-bi %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>