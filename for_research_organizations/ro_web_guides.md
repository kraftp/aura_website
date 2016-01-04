---
layout: post
title: Research Organization Web Guides
---

<div class="row">
	<div id="portofolio">
    {% for post in site.categories.ro %}
		<div class="six columns">
			<h5><a href="{{post.url}}">{{post.title}}</a></h5>
			<p>By {{post.author}}</p>
			<div class="portofoliothumb">
				<img src="/images/guides/{{post.image}}" class="fourimage" alt=""/>
			</div>
		</div>
    {% endfor %}
	</div>
</div>
