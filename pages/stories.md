---
layout: blog
title: "Shenanigans.lol Stories"
teaser: "This is the Shenanigans.lol Stories Template"
header:
    image_fullwidth: "header-bus.jpg"
    permalink: /stories/
---
<ul>
    {% for post in site.categories.stories %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
