---
layout: page
title: Blog
permalink: /blog/
---

<head>
<link rel="stylesheet" type="text/css" href="/css/blog.css" />
</head>
<body>

{% for post in site.posts %}
<br>
<span class="post-meta">{{ post.date | date: "%b %-d, %Y" }} </span>
	<div class="image" style="background-image: url('{{post.imgurl}}')" > 
		<div class="post-box"> <a class="post-link" href="{{ post.url }}"> {{post.title}} </a> {{post.blog_excerpt}} </div>
	</div>


{% endfor %}
</body>
