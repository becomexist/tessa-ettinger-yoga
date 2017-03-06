---
layout: default
---

<div class="about-columns">
	<div class="about-tessa">
		<h1>{{ page.main_heading }}</h1>
		{{ page.intro_text || markdownify }}
	</div>

	<div class="tessa-profile">
		<img class="image-circle" src="{{ site.baseurl }}/assets/images/square-tessa.jpg" />
	</div>
</div>

<div class="details-container">
	<div class="tessa-details">{{ page.secondary_text || markdownify }} </div>

	{% include private_yoga_button.html %}
	
</div>

{% include flower_pattern.html %}
