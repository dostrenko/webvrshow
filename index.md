---
layout: home
title: Home
landing-title: Immersive Expressions
description:
image:
author:
nav-menu:
---

<!-- Banner -->
<section id="banner" class="major">
	<div class="inner">
		<header class="major">
			<h1>{{ page.landing-title }}</h1>
		</header>
		<div class="content">
			<p style="text-transform: uppercase;">{{ site.description }}</p>
			<ul class="actions">
				<!-- <li><a href="#one" class="button next scrolly">Submit in	 Nov.</a></li> -->
			</ul>
		</div>
	</div>
</section>

<!-- Main -->
<div id="main">

<!-- Two -->
<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Call for Work</h2>
		</header>

			{% include call.html %}

		<ul class="actions">
			<li><span class="button">Submit your work starting November 20, 2016</span></li>
		</ul>
	</div>
</section>

<!-- One -->
{% include tiles.html %}

</div>
