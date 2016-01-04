---
layout: post
title: Student Web Guides
---

<div class="row">
	<div id="portofolio">
    {% for post in site.categories.student %}
		<div class="six columns">
			<h5><a href="{{post.url}}">{{post.title}}</a></h5>
			<div class="portofoliothumb">
				<img src="/images/guides/{{post.image}}" class="fourimage" alt=""/>
			</div>
		</div>
    {% endfor %}
	</div>
</div>