---
layout: page
title: Decoded Bits
tagline: 
---
{% include JB/setup %}
    
## All Blog Entries

<ul class="posts">
  {% for post in site.posts %}
    <li><h4><span><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></h4>
    <h4> <small class="text-muted">{{post.excerpt}} </small></h4>
    </li>
  {% endfor %}
</ul>
