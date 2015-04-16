---
layout: page
title: Welcome!
tagline: Supporting tagline
---
{% include JB/setup %}

This is an awesome time to be a developer.

>
> Code is basically everywhere, smeared over everything we do like an invisible icing on the cake of life.
> 

I am a software developer and I know I have the ‘power to create‘.


   
## Latest

Here are my recent rants

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




