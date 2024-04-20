---
layout: page
title: Welcome
regenerate: true
---

‘UX Talk Tokyo’ is a User Experience discussion and networking group in Tokyo.

We hold in-person events in various locations in Tokyo. It’s for anyone interested in UX. Some of the people who come do UX as their job, but there are many other types of people … developers, designers, students. Everyone is welcome. And it’s for Japanese and non-Japanese. The presentations are in English, but of course the networking is in Japanese or English (many people can speak both).

If you’re interested, please sign up to the email list. And please feel free to get in touch with us.

![Photo of event](/assets/images/2016-09-13/CF8D3393-2534-40CF-8ADE-564E841C51BE_1_105_c.jpeg)

![Photo of event](/assets/images/2016-10-26/0A0EA0B5-9B07-4ABD-BBD0-06E402547501_1_105_c.jpeg)

![Photo of event](/assets/images/2016-10-26/A12C8A1D-B5D2-49D8-B050-7ACAEC6DEF82_1_105_c.jpeg)

![Photo of event](/assets/images/2016-11-21/08EE80D6-4528-415D-BDFE-4BB07896C47C_1_105_c.jpeg)

![Photo of event](/assets/images/2016-11-21/3262B189-5C9E-4069-87E5-113AA47715EE_1_105_c.jpeg)

And it is occasionally said that the after-party is the _main_ event.

![After-party photo](/assets/images/2016-09-13/CF8D3393-2534-40CF-8ADE-564E841C51BE_1_105_c.jpeg)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.snippet }}</p>
    </li>
  {% endfor %}
</ul>
