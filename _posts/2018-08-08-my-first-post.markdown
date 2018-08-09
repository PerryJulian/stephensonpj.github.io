---
permalink: /Travels
title: Adventures
catergory: test
---
Where have I gone

Here is a picture

![Santa Monica]({{ "/assets/test.jpg" | absolute_url }})
![Santa Monica]({{ "/assets/test2.jpg" | absolute_url }})

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>