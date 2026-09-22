---
layout: default
title: dates
---

<h1>{{ page.title }}</h1>

{% for date in site.data.dates %}
<p>
{{ date.datum }}
<br>
{{ date.naam }}
</p>
{% endfor %}

