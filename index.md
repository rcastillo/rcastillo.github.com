---
layout: page
title: Home
tagline: 
---
{% include JB/setup %}

### Open Source Projects
* [SiteQuery](https://github.com/rcastillo/sitequery) - An targeted web crawler built on node.js
* [qrx](https://github.com/loku/qrx) - A distributed node.js work queue built on redis
* [TicTacNode](https://github.com/loku/tictacnode) - A simple game based on socket.io, backbone.js and node.js 


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




