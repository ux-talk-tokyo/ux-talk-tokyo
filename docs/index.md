---
layout: page
title: Welcome
regenerate: true
---
‘UX Talk Tokyo’ is a User Experience discussion and networking group in Tokyo.

We hold in-person events in various locations in Tokyo. It’s for anyone interested in UX. Some of the people who come do UX as their job, but there are many other types of people … developers, designers, students. Everyone is welcome. And it’s for Japanese and non-Japanese. The presentations are in English, but of course the networking is in Japanese or English (many people can speak both).

If you’re interested, please sign up to the email list. And please feel free to get in touch with us.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.snippet }}</p>
    </li>
  {% endfor %}
</ul>
