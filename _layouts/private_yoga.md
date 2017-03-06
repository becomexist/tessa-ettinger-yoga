---
layout: default
---

<div id="private-yoga-page">
	<h1>Private Yoga</h1>
	<img class="line" width="100px" src="{{ site.baseurl }}/assets/images/line.png" />
	<h2 class="amatic">North London</h2>

	<img id="meditation" class="yoga-dude" src="{{ site.baseurl }}/assets/images/yoga_dudes/meditation.png" width="100px" />

	<div id="north-london">
		{{ page.intro_text | markdownify }}
	</div>

	<div id="how">
		{{ page.secondary_text | markdownify }}
	</div>
</div>

{% include small_pattern.html %}

<div id="private-yoga-form">		
	<h2>Get in touch</h2>
	<p>If you are interested in private yoga lessons, feel free to leave your details below:</p>

	<form action="https://formspree.io/tessa@privateyoganorthlondon.com" method="POST">
		{% include form.html %}
	</form>
</div>

{% include peacock_pattern.html %}
