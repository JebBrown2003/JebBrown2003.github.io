---
layout: home
title: Home
---

## Start here

A few pieces that best represent the kind of work and thinking on this site:

- **Post Title #1**  
  _What this project was trying to answer_

- **Post Title #2**  
  _A concrete system design or modeling lesson_

- **Post Title #3**  
  _An end-to-end walkthrough worth reading first_

---

## Recent writing

{% for post in site.posts limit:6 %}
- **[{{ post.title }}]({{ post.url }})**  
  <small>{{ post.date | date: "%B %d, %Y" }}</small>
{% endfor %}

---

<small>
Read more about this blog and about me on the <a href="/about/">About</a> page.
</small>
