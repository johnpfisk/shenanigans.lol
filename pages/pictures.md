---
layout: page
show_meta: false
title: "Pictures"
subheadline: "Silly&hellip;"
header:
    image_fullwidth: "header-bus.jpg"
permalink: "/pictures/"
---
<ul>
    {% for post in site.categories.pictures %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>