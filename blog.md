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
<table>
	<tr> 
<li class="image" style="background: url('{{post.imgurl}}')" > </li>
	<li> <a class="post-link" href="{{ post.url }}"> {{post.title}}</a>{{post.blog_excerpt}} </li>
	</tr>
</table>
</div>


</li>
{% endfor %}

</ul>
</body>





