---
layout: page
show_meta: false
title: "SQL Server"
subheadline: "Querying"
header:
   image_fullwidth: "leh3.jpg"
permalink: "/sql/"
---
<ul>
    {% for post in site.categories.sql %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>