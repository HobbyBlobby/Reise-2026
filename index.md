---
layout: default
---

# Übersicht
Diese Seite dient als Reistagebuch. Beständiger und schöner als eine WhatsApp-Status. 
Wer gerne stöbern möchte, ist gerne dazu eingeladen. 

## Reisetagebuch: Die Kapitel

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/Reise-2026{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>
