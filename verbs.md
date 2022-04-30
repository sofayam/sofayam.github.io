---
layout: default
---
Welcome to the verbs

<ul>
  {% for verb in site.verbs %}
    <li>
      <a href="{{ verb.url }}">{{ verb.title }}</a> 
    </li>
  {% endfor %}
</ul>