---
layout: page
show_meta: false
title: "Design Considerations"
subheadline: "Views"
header:
   image_fullwidth: "leh4.jpg"
permalink: "/design/"
---
<ul>
    {% for post in site.categories.design %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>