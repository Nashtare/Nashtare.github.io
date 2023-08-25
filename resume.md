---
layout: page
title: Resume
---

{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.date | date: "%B %Y" }} - {{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}

[Download](https://Nashtare.github.io/resume.pdf)

<embed src="https://Nashtare.github.io/resume.pdf" type="application/pdf" style="min-height:100vh;width:100%"/>