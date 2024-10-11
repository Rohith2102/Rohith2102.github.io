---
title: "Talks"
permalink: /talks/
---

# Talks

{% for talk in site.talks %}
- **{{ talk.title }}**
  - Event: {{ talk.event }}
  - Date: {{ talk.date | date: "%B %d, %Y" }}
  - [Read More]({{ talk.url }})
{% endfor %}
