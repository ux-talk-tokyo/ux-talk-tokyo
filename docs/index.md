---
layout: page
title: Welcome to UX Talk Tokyo
---

# Welcome to UX Talk toky
‘UX Talk Tokyo’ is a User Experience discussion and networking group in Tokyo. We meet once a month, usually on a Wednesday from 7pm-9pm at Gengo’s office in Shibuya.

It’s for anyone interested in UX. Some of the people who come do UX as their job, but there are many other types of people … developers, designers, students. Everyone is welcome. And it’s for Japanese and non-Japanese. The presentations are in English, but of course the networking is in Japanese or English (many people can speak both).

If you’re interested, please sign up to the email list. And please feel free to get in touch with us.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
