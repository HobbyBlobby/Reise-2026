---
layout: default
---

# Reise-2026
Ein Reisetagebuch für mein kleines Abenteuer.

Klicke den Link für den entsprechenden Reiseabschnitt.

## Reisetagebuch

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

[Nur eine Testseite](./test.md)
