---
layout: page
collection: docpages
title: Quickstart
permalink: /docs/quickstart/
---

___Don't use for production yet. Only for fun___

<!-- Sort quickstart_parts collection -->
{% assign items = site.quickstart_parts | sort: 'number' %}

{% for part in items %}

{{ part.title }}
----------------
{{ part.content }}

{% endfor %}
