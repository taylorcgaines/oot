---
layout: page
title: Characters (Who We Are)
permalink: /bio-landing/
---

I'm going to put a collection of characters here, to mirror the collection of bios that will go on the real site.

{% for character in site.characters %}
  <div class="character">
    <h2><img src="{{ character.image_path }}" alt="{{ character.title }}"><a href="{{ character.url }}">{{ character.title }}</a></h2>
  </div>
{% endfor %}
