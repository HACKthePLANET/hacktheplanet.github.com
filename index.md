---
layout: page
title:
tagline: 
---
{% include JB/setup %}

## Code

Collaborate on hacks inside the [GitHub HackThePlanet organization](https://github.com/HackThePlanet ). 

We hang out on irc.freenode.net inside the [##gibson](irc://irc.freenode.net:4443/%23%23gibson ).

## Videos <small>(<a href="/videos.html">All</a>)</small>

<div class="row" style="margin-bottom: 10px;">
  <div class="span3">
    <p><b><a href="http://creepagram.com/">Creepagram</a></b><br /><span style="color:grey;">1st Place Demo at Node.js Hackday</span></p>
    <p>Instagram + Google Street View Panoramas</p>
    <p><a href="https://github.com/mindflash/creepagram" class="btn btn">More &raquo;</a></p>
    <iframe src="http://player.vimeo.com/video/38053195?portrait=0" width="201" height="113" frameborder="0" >
      Creepagram
    </iframe>
  </div>

  <div class="span3">
    <p><b>Cloud Crypto</b><br /><span>&nbsp;</span></p>
    <p>transparent crypto proxy for cloud files</p>
    <p><a href="https://github.com/philips/cloudfiles-crypto-proxy" class="btn btn">More &raquo;</a></p>
  </div>

  <div class="span3">
    <p><b>Request-JSONStream</b><br /><span style="color:grey;">3rd Place Demo at Node.js Hackday</span></p>
    <p>Send or receive JSON as newline delimited object via request</p>
    <p><a href="https://github.com/smurthas/Request-JSONStream" class="btn btn">More &raquo;</a></p>
  </div>
</div>

## Events

<ul class="posts">
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
      {% if post.title == "Elastic Search Hackday" %}
        <span class="label label-warning"><a href="http://elasticsearchhackday.eventbrite.com/">register!</a></span>
      {% endif %}
      {% if post.title == "Data Visualization Hackday" %}
        <span class="label label-warning"><a href="http://datavizhackday.eventbrite.com/">register!</a></span>
      {% endif %}
    </li>
  {% endfor %}
</ul>

## Proposals

We're looking for:

<ul>
  <li>Tech Talks at upcoming events</li>
  <li>Event ideas</li>
  <li>Challenges</li>
</ul>

Use any of the following mechanisms to communicte:

<ul>
  <li>Email <a href="mailto:lucy.mendel@rackspace.com">lucy.mendel@rackspace.com</a>.</li>
  <li>Submit a pull request for a <a href="https://github.com/HackThePlanet/hacktheplanet.github.com/tree/master/_posts">new event</a>.</li>
  <li>Create an <a href="http://github.com/hacktheplanet/hacktheplanet.github.com/issues">issue</a> with ideas, bugs andPP feature requests.</li>
</ul>
