---
layout: default
---

<div class="lead-quote">
	<blockquote class="jois-quote"><em>{{ page.quote }}</em></blockquote>
	<p class="quote-source">— {{ page.quote_source }}</p>
</div>

<div class="yoga-dudes">
	<div class="dude-column" id="tree-pose">
		<img class="yoga-dude" src="{{ site.baseurl }}/assets/images/yoga_dudes/tree-pose.png" />
	</div>
	<div class="dude-column" id="triangle">
		<img class="yoga-dude" src="{{ site.baseurl }}/assets/images/yoga_dudes/triangle.png" />
	</div>
	<div class="dude-column" id="side-bend">
		<img class="yoga-dude" src="{{ site.baseurl }}/assets/images/yoga_dudes/side-bend.png" />
	</div>
</div>

<blockquote class="intro-message"> It doesn’t matter if you’re big or little, stiff or flexible, injured, healthy, old, young, happy, sad, blue, green, square, hexagonal… Yoga can still be possible for you. </blockquote>

{% include dot_pattern.html %}

<div id="reasons">
	<div class="narrow-columns">
		{{ page.main_text | markdownify }}

		{% include private_yoga_button.html %}
	</div>
</div>

{% include cactus_pattern.html %}
