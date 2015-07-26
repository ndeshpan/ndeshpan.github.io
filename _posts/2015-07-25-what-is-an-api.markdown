---
layout: post
title: "What Is An API?"
date: 2015-07-25 10:00:00
meta: "Clarification on a subject I have been meta confused about"
categories: jekyll update
tags:
- -api
blog_excerpt: At my internship, I keep hearing the word API. Its tossed around the way kindergardeners ask the question "why"; people reference it constantly, and the more its mentioned, my mind becomes more muddled. So here is an attempt to unpack the uncertainty, and understand the core tenets of an API! 
imgurl: http://www.mashery.com/sites/default/files/styles/640x480/public/fields/field_image_row/api-management.png?itok=EmhuIme0
---
<h1> The Basics </h1>
After much research, here it what I found:

Simply put, an API is basically a link. It allows you to leverage the data/resources of some software for personal use. The API acts like a messenger, tells the system what you want to do, and returns the response back to you. The API's role is comparable to a waiter acting as a messenger between you and the kitchen. 

On a typical airline website, you enter you anticipated arrival and departure dates & locations. In essence, by specifying certain variables, you interact with the airline site's database to see if anything meets your requirements. Lets say you decide to book your travel tickets using Expedia instead of the stock British Airways site. How does Expedia access British Airways' database to provide you with information on whether flights match your travel dates? Expedia doesn't have direct access to this database....Ah-ha! This is where the API comes into play. Expedia will interact with British Airways' API to provide you real-time information on BA flights by accessing the airline's database; you request certain variables, it queries the database, and then returns the information to you on Expedia. 

API's drive connectivity! How cool is that?! 

<h2> REST API </h2>
Let's begin with the foundation: REST stands for REpresentational State Transfer, and API stands for Application Programming Interface. Usually, a REST API works the same way a website does; a call is made from the client to the server, and you get data back through the HTTP protocol. 

(completely irrelevant tidbit: JSON stands for javascript objet notation, organized according to key value pairs--who knew? Apparently I didn't.)

This research is leading me to research HTTP request methods...so slight tangent.

<h2> HTTP Request Methods & API's</h2>
There are two main request methods: 
<ul>
	<li> GET: use to consume data, and get data back (...perhaps from an API)</li>
	<li> POST: use to write data to an API, put the data in the body of an HTTP request </li>
</ul>


