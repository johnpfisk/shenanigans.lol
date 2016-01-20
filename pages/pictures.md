---
layout: blog
title: "Shenanigans.lol Picture Articles"
teaser: "This is the Shenanigans.lol Picture Article Template"
header:
    image_fullwidth: "header-bus.jpg"
    permalink: /pictures/
---
<ul>
    {% for post in site.categories.pictures %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>