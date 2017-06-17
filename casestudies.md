---
---

<ul class="list pa0">
  {% for post in site.posts %}
  <li class="mv2">
    <a href="{{ site.url }}{{ post.url }}" class="db pv1 link blue hover-mid-gray">
      {{ post.title }}
    </a>
  </li>
  {% endfor %}
</ul>
