---
title: Damian Karzon
layout: page
permalink: /team/damian-karzon/
---

<div class="memberdetails row-fluid">
	<div class="span2 sidebar">
		<img src="http://1.gravatar.com/avatar/1ea2829caf0b9135cd7ece795ccde774?size=72" border="0" alt="Author" class="authimg" />
		<ul class="memberlinks">
			<li class="blog"><a href="http://dkdevelopment.net">Damian's Blog</a></li>
			<li class="twitter"><a href="https://twitter.com/d1k_is">Twitter</a></li>
		</ul>
	</div>

	<div class="span10">
		<p><em>Lead Software Developer</em></p>

		<p>
			Damian is a .NET developer who has been working with Ardent Leisure since early 2009.
		</p>

		<p>With over 5 years experience in software development.</p>

		<h3>Posts by Damian</h3>
		<ul>
			{% for dkpost in site.categories.DK limit: 10 %}
				<li><a href="{{ dkpost.url }}" title="{{ dkpost.title }}">{{ dkpost.title }}</a></li>
			{% endfor %}
		</ul>
	<div>

</div>