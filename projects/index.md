---
layout: page
title: Projects
excerpt: "An archive of projects sorted by date."
image:
    feature: galaxy.png
---
<ul class="post-list">
{% for post in site.categories.projects %} 
  <li><article><a href="{{post.permalink}}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>
