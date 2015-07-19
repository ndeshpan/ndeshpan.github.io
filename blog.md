---
layout: page
title: Blog
permalink: /blog/
---

<head>
<link rel="stylesheet" type="text/css" href="/css/blog.css" />
</head>
<body>

<ul class="post-list">
{% for post in site.posts %}

<li>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} </span>

<div class="post-container">
<table class="post-container">
<tr class="post-container">
<h2>
	
<a class="post-link" href="{{ post.url }}">{{post.title}}</a>
</h2>
{{post.blog_excerpt}}
</tr>
</table>
</div>


</li>
{% endfor %}

</ul>
</body>
