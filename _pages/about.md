---
permalink: /
title: "About"
excerpt: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Research Fellow (pre-doctoral researcher) working full time at Microsoft Research (MSR) with [Dr. Nagarajan Natarajan](https://www.microsoft.com/en-us/research/people/nagarajn/) and [Dr. Jayashree Mohan](https://www.microsoft.com/en-us/research/people/jamohan/), where I apply machine learning to problems in the area of systems. I have recently become interested in generative modelling, low-resource and low-latency inference, robustness and security. In general, I am interested in machine learning and its applications towards other areas, such as computer vision. 

In my free time I like to read, write and learn the violin.

<h2>Recent News</h2>

	  {% for post in site.posts %}
	    <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
	</ul>
