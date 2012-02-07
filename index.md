---
layout: page
title:
tagline: 
---
{% include JB/setup %}

## Code

Collaborate on hacks [here](https://github.com/HackThePlanet )

## Events and Challenges

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Propose an Event or Challenge

<ul class="unstyled">
  <li>Submit a <a href="https://github.com/HackThePlanet/hacktheplanet.github.com/tree/master/_posts">new post</a> Pull Request.</li>
  <li><a href="http://github.com/hacktheplanet/hacktheplanet.github.com/issues">Issue a theme request</a>.</li>
  <li>Email <a href="mailto:hacktheplanet@lists.rackspace.com">hacktheplanet@lists.rackspace.com</a>.</li>
</ul>
