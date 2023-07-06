---
title: Recipes
layout: default
---
{% comment %}
  This page is .html instead of .md so that the include below outputs
  HTML instead of being processed as Markdown.
{% endcomment %}

{% for recipe in site.recipes %}
  <p><a href="{{ recipe.url }}">{{ recipe.title }}</a></p>
{% endfor %}