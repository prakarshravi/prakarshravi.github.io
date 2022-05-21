---
layout: page
show_meta: false
title: "Python"
subheadline: "Scripts"
header:
   image_fullwidth: "leh4.jpg"
permalink: "/python/"
---
<ul>
    {% for post in site.categories.python %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>