---
layout: blog
title: "Shenanigans.lol Video Articles"
teaser: "This is the Shenanigans.lol Video Article Template"
header:
    image_fullwidth: "header-bus.jpg"
    permalink: /videos/
---
<ul>
    {% for post in site.categories.videos %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>