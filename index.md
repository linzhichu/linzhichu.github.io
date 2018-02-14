---
layout: page
title: Decoded Bits
tagline: 
---
{% include JB/setup %}
    
## All Blog Entries

<ul class="posts">
  {% for post in site.posts %}
    <li><h4><span><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></span></h4>
    <h4><small class="text-muted">{{post.date}}
    {% for category in post.categories%}
    <span class="badge badge-light">{{category}}</span>
    {% endfor %}
    {% for tag in post.tags%}
    <span class="badge badge-light">{{tag}}</span>
    {% endfor %}
    </small></h4>
    <h4> <small class="text-muted">{{post.excerpt}} </small></h4>
    </li>
    <br>
  {% endfor %}
</ul>
