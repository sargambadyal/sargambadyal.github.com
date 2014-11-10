---
layout: page
title: Sargam Badyal's Blog Space
tagline: Welcome Awesomness!!
---
{% include JB/setup %}

Checkout [My Github ](https://github.com/sargambadyal)

## About This Blog

Its a post to share all my learning with you and expand my knowledge.

## My Posts

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Also Check

" yet to think "


