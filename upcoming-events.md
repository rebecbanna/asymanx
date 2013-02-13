---
layout: page
title: Upcoming Events
tagline: 
---
{% include JB/setup %}

## Events

- 22 Feb 2013 Benefit Contra With David Kaynor, @Guiding Star Grange [facebook event page](https://www.facebook.com/events/411420575609291/),
  [printable version of flyer (pdf)](/assets/posters/contradance-medium.pdf), [COLOR printable version of flyer (pdf)](/assets/posters/contradance-color-medium.pdf)

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
