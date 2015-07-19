---
layout: page
title: Tags
permalink: /tags/
---
<html>
<head>
<link rel="stylesheet" type="text/css" href="/css/tags.css" />
</head>
<body>


{% capture tags %}
  {% for tag in site.tags %}
    {{ tag[0] }}
  {% endfor %}
{% endcapture %}
{% assign sortedtags = tags | split:' ' | sort %}

{% for tag in sortedtags %}
  <p id="tag">{{ tag }}</p>
  <ul>
  {% for post in site.tags[tag] %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
  </ul>
{% endfor %}
</body>
</html>