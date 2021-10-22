---
layout: default
---

# News

{% for news in site.data.news %}
  * <b>{{ news.date }}:</b> {{ news.text }}
{% endfor %}
