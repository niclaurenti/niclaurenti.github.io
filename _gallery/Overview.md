---
layout: gallery
title: Gallery
permalink: /gallery/
support: [jquery, gallery]
---

{% assign count = 0 %}
{% assign align = "left" %}
{% for gallery in site.data.galleries.overview %}
{% if count == 0 %}<div class="row">{% endif %}
  <div class="half-width gallery-preview {{ align }}">
    <h2>{{ gallery.title }}</h2>
    <a href="{{ gallery.directory }}">
      <img alt="{{ gallery.title }}" src="/assets/gallery/{% if gallery.picture_path %}{{ gallery.picture_path }}{% else %}{{ gallery.directory }}{% endif %}/{{ gallery.preview.thumbnail }}" style="width:40%"/>
    </a>
  </div>
{% if count == 1 %}</div>{% endif %}
{% assign count = count | plus: 1 %}
{% assign align = "right" %}
{% if count >= 2 %}
{% assign align = "left" %}
{% assign count = 0 %}
{% endif %}
{% endfor %}

{% if count != 1 %}
{% endif %}