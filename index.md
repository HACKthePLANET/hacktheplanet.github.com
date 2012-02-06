---
layout: page
title: HackThePlanet
---
{% include JB/setup %}

## Propose a Hacking Event or Challenge

<ul class="unstyled">
  <li>Submit a Pull Request with a <a href="https://github.com/HackThePlanet/hacktheplanet.github.com/tree/master/_posts">new event post</a>.</li>
  <li><a href="http://github.com/hacktheplanet/hacktheplanet.github.com/issues">Issue a theme request</a>.</li>
  <li>Email <a href="mailto:hacktheplanet@lists.rackspace.com">hacktheplanet@lists.rackspace.com</a>.</li>
</ul>

## Monthly SF HackDays

Every <b>first Wednesday</b> of the month at 
[Rackspace's San Francisco Office](http://maps.google.com/maps?q=620+Folsom+Street,+San+Francisco,+CA,+United+States&hl=de&sll=37.0625,-95.677068&sspn=48.77566,92.724609&oq=620+Folsom+S&hnear=620+Folsom+St,+San+Francisco,+California+94105&t=m&z=16)

<ul class="unstyled">
  <li>9am: Start hacking</li>
  <li>6pm: Start demos</li>
  <li>8pm: Get dinner and/or move to a local bar</li>
</ul>

## Events

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
