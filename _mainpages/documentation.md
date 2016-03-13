---
layout: page
collection: main_pages
title: Documentation
permalink: /docs/
---

{% for docpage in site.docpages %}
* [{{ docpage.title }}]({{ docpage.url | prepend: site.baseurl }})
{% endfor %}
