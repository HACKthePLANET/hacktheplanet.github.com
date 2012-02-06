---
layout: page
title: HackThePlanet
---
{% include JB/setup %}

## Propose a Hacking Event or Challenge

Submit a Pull Request with an event post in <a>asdf</a> and/or send email to <a href="mailto:hacktheplanet@lists.rackspace.com">hacktheplanet@lists.rackspace.com</a>.

## Monthly SF HackDays

Every <b>first Wednesday</b> of the month at 
[Rackspace's San Francisco Office](http://maps.google.com/maps?q=620+Folsom+Street,+San+Francisco,+CA,+United+States&hl=de&sll=37.0625,-95.677068&sspn=48.77566,92.724609&oq=620+Folsom+S&hnear=620+Folsom+St,+San+Francisco,+California+94105&t=m&z=16)

<ul class="unstyled">
  <li>9am: Start hacking</li>
  <li>6pm: Start demos</li>
  <li>8pm: Get dinner and/or move to a local bar</li>
</ul>

Send theme requests to <a href="mailto:hacktheplanet@lists.rackspace.com">hacktheplanet@lists.rackspace.com</a>

## Events

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
