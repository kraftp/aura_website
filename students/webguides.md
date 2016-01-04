---
layout: post
title: Student Web Guides
---

<div class="row">
	<div id="portofolio">
		{% assign sorted_posts = (site.categories.student | sort: 'title') %}
    {% for post in sorted_posts %}
		<div class="six columns">
			<h5><a href="{{post.url}}">{{post.title}}</a></h5>
			<p>By {{post.author}}</p>
			<div class="portofoliothumb">
				<img src="/images/guides/{{post.image}}" class="threeimage" alt=""/>
			</div>
		</div>
    {% endfor %}
	</div>
</div>
