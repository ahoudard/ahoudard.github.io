---
layout: page
title: Test
permalink: /test/
---

<div class="publications">
  {% for post in site.publications %}
    <article class="publications">

      <h1><a href="{{ site.baseurl }}{{ publications.url }}">{{ publications.title }}</a></h1>

      <div class="entry">
        {{ publications.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ publications.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>