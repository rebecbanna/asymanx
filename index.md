---
layout: page
title: And Sometimes Y Manx Morris & Sword
tagline: Supporting tagline
---
{% include JB/setup %}

And Sometimes Y Manx Morris & Sword is a youth fol dance team, founded in 2010, Based in the Pioneer Valley of Western Massachusetts. ASY does dances in the Sherbourne tradition, but specializes in dances from the Isle of Mann.

We are currently fundraising to visit the Isle of Mann in July, 2013. Our goal is to raise (a certain amount) by (a certain date). If you feel like donating, head over to our Kickstarter (a work in progress!), or click the donate button (below, on the left/right, insert directional instruction here)

And then maybe a couple boxes (or links or whatever) with peeks of other pages, like latest blog post, or pictures from the gallery, or see our videos here.

- [Manx Dancing](manx-dancing.html)
- [Practices](practices.html)
- [Upcoming Events](upcoming-events.html)
- [Contact Us](contact.html)

(There should be a picture of us, or something)
    
## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
