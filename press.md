---
title: Press
layout: posts_list
navigation_weight: 5
slug: press
meta_content: Tessa Ettinger's features in the press
---

{% for post in site.posts %}
	{% if post.categories contains "press" %}
		<div class="post">
			<a href="{{ post.url }}"><h4>{{ post.title }}</h4>
				<p>{{ post.date | date: "%d %B %Y" }}</p>
			</a>
			{% if post.featured_video %}
	      {{ post.featured_video }}
	    {% else %}
	      <a href="{{ post.url }}"><img src="{{ post.featured_image }}" alt="{{ post.featured_alt }}" /></a>
	    {% endif %}	
		</div>
	{% endif %}
{% endfor %}

{% include dot_pattern.html %}