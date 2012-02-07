---
layout: page
title:
tagline: 
---
{% include JB/setup %}

## Code

Collaborate on hacks [here](https://github.com/HackThePlanet ).

<br />

<div class="row">
  <div class="span1"><p></p></div>

  <div class="span3">
    <p><b>Twisted-Hang</b></p>
    <p>Figure out if the main thread is hanging, and if so, why.</p>
    <p><a href="https://github.com/HackThePlanet/twisted_hang" class="btn btn-primary">More &raquo;</a></p>
  </div>

  <div class="span3">
    <p><b>AMP Repl</b></p>
    <p>Terminal-based REPL to interact with AMP</p>
    <p><a href="https://code.launchpad.net/~exarkun/+junk/amp-repl" class="btn btn-primary">More &raquo;</a></p>
  </div>

  <div class="span3">
    <p><b>Slogger</b></p>
    <p>slog through your irc logs and toss 'em into elastic search</p>
    <p><a href="https://github.com/morgabra/slogger" class="btn btn-primary">More &raquo;</a></p>
  </div>
</div>

<br />

## Events and Challenges

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      {% if post.title == "Node Js Hackday" %}
        <span class="label label-warning">register!</span>
      {% endif %}
    </li>
  {% endfor %}
</ul>

## Propose an Event or Challenge

<ul class="unstyled">
  <li>Submit a <a href="https://github.com/HackThePlanet/hacktheplanet.github.com/tree/master/_posts">new post</a> Pull Request.</li>
  <li><a href="http://github.com/hacktheplanet/hacktheplanet.github.com/issues">Issue a theme request</a>.</li>
  <li>Email <a href="mailto:hacktheplanet@lists.rackspace.com">hacktheplanet@lists.rackspace.com</a>.</li>
</ul>
