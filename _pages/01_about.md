---
layout: 
title: About
permalink: /about/
---

{% include head.html %}

<div class="container">
<div class="banner">
	<img src="{{"/assets/enterBanner.PNG"}}">
	<!-- <h1><a href="{{ site.baseurl }}">{{ site.title }}</a></h1> -->
</div>


	
		<nav>
			<ul>
				{% for page in site.pages %} {% if page.title %}
				<li><a href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a></li>
				{% endif %} {% endfor %}
				<li><a href="{{ "/blog" | prepend: site.baseurl }}">Blog</a></li>
			</ul>
			
			
		</nav>
	</div>

About content goes here.

* A list item
* Another list item
