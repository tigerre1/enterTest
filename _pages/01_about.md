---
layout: default
title: About
permalink: /about/
---



{% capture site_tags %}{% for tag in site.tags %}{{ tag | first }}{% unless forloop.last %},{% endunless %}{% endfor %}{% endcapture %}
                {% assign sortedTags = site_tags | split:',' | sort %}
                
<h1>{{site_tags | split:','}}</h1>


