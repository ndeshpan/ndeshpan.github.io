---
layout: page
title: Blog
permalink: /blog/
---

<head>
<style>
	.post-container {
		background-color:#4dc9ff ;
		border-radius:15px;
		border: 2px solid black;
	}



</style>
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
