---
layout: page
title: Welcome
regenerate: true
---

‘UX Talk Tokyo’ is a networking and learning group in Tokyo. We hold events in central Tokyo, with presentations on varied topics related to UX.

It’s for anyone interested in UX. Some of the people who come do UX as their job, but there are many other types of people … developers, designers, students. Everyone is welcome.

It’s for Japanese and non-Japanese. Presentations are usually in English, although they usually have Japanese subtitles. Networking is in Japanese or English (many people can speak both).

If you’re interested, please sign up to the email list on [Doorkeeper](https://uxtalktokyo.doorkeeper.jp/). And please feel free to get in touch with us [here](https://uxtalktokyo.doorkeeper.jp/contact/new).

![Photo of event](/assets/images/2016-10-26/0A0EA0B5-9B07-4ABD-BBD0-06E402547501_1_105_c.jpeg)

![Photo of event](/assets/images/2016-11-21/08EE80D6-4528-415D-BDFE-4BB07896C47C_1_105_c.jpeg)

![Photo of event](/assets/images/2016-11-21/3262B189-5C9E-4069-87E5-113AA47715EE_1_105_c.jpeg)

![Photo of event](/assets/images/2023-06-21/344976AF-551B-4BB4-97C9-9C66C201E66F_1_105_c.jpeg)

And it is occasionally said that the after-party is the _main_ event. We especially hope first-time attendees can join.

![After-party photo](/assets/images/2016-09-13/CF8D3393-2534-40CF-8ADE-564E841C51BE_1_105_c.jpeg)

# Event list

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.snippet }}</p>
    </li>
  {% endfor %}
</ul>
