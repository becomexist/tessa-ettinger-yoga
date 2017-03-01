---
title: Blog
layout: posts_list
navigation_weight: 6
slug: blog
meta_content: Tessa Ettinger's personal Yoga Blog
---

{% for post in site.posts %}
	{% unless post.categories contains "press" %}
		<div class="post">
			<a href="{{ post.url }}"><h4>{{ post.title }}</h4>
			<p>{{ post.date | date: "%d %B %Y" }}</p>
			<img src="{{ post.featured_image }}" alt="{{ post.featured_alt }}"></a>
		</div>
	{% endunless %}
{% endfor %}

{% include dot_pattern.html %}