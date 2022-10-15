---
layout: default
title: topics
---
<h1>Topics</h1>

<ul>
  {% for topic in site.topics %}
    <li>
      <h2>{{ topic.name }}</h2>
      <p>{{ author.content | markdownify }}</p>
    </li>
  {% endfor %}
</ul>