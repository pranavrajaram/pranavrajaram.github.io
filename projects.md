---
layout: page
title: Projects
permalink: /projects/
---

Here is a collection of various projects I have worked on over the past few years:
<hr>

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

        
      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
