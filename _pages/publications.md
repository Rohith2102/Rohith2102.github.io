---
title: "Publications"
permalink: /publications/
---

# Publications

{% for pub in site.publications %}
- **{{ pub.title }}**
  - Authors: {{ pub.authors }}
  - *{{ pub.journal }}, {{ pub.year }}*
  - [DOI Link]({{ pub.doi }})
  - [Read More]({{ pub.url }})
{% endfor %}
