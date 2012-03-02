---
layout: page
title:
tagline: 
---
{% include JB/setup %}

## Code and Chat

Collaborate on hacks inside the [GitHub HackThePlanet organization](https://github.com/HackThePlanet ). 

Chat with us on irc.freenode.net inside the [##gibson](irc://irc.freenode.net:4443/%23%23gibson ).

<br />

<div class="row">
  <div class="span1"><p></p></div>

  <div class="span3">
    <p><b>Twisted-Hang</b></p>
    <p>Figure out if the main thread is hanging, and if so, why.</p>
    <p><a href="https://github.com/HackThePlanet/twisted_hang" class="btn btn">More &raquo;</a></p>
  </div>

  <div class="span3">
    <p><b>AMP Repl</b></p>
    <p>Terminal-based REPL to interact with AMP</p>
    <p><a href="https://code.launchpad.net/~exarkun/+junk/amp-repl" class="btn btn">More &raquo;</a></p>
  </div>

  <div class="span3">
    <p><b>Slogger</b></p>
    <p>slog through your irc logs and toss 'em into elastic search</p>
    <p><a href="https://github.com/morgabra/slogger" class="btn btn">More &raquo;</a></p>
  </div>
</div>

<br />

## Events and Challenges

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      {% if post.title == "Intern Hackday" %}
        <span class="label label-warning"><a href="http://internhackday.eventbrite.com/">register!</a></span>
      {% endif %}
    </li>
  {% endfor %}
</ul>

## Proposals

We're looking for:

<ul>
  <li>Events</li>
  <li>Challenges</li>
  <li>Tech Talks</li>
</ul>

Use any of the following mechanisms to communicte:

<ul>
  <li>Submit a pull request for a <a href="https://github.com/HackThePlanet/hacktheplanet.github.com/tree/master/_posts">new post</a>.</li>
  <li>Create an <a href="http://github.com/hacktheplanet/hacktheplanet.github.com/issues">Issue</a>.</li>
  <li>Email <a href="mailto:lucy.mendel@rackspace.com">lucy.mendel@rackspace.com</a>.</li>
</ul>
