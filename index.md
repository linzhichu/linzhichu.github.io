---
layout: page
title: Decoded Bits
tagline: 
---
{% include JB/setup %}
    
## All Blog Entries

<ul class="posts">
  {% for post in site.posts %}
    <li><h4><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h4></li><br>
    <h4><small class="text-muted">{{post.excerpt}}</small></h4>
  {% endfor %}
</ul>
