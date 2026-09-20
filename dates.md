---
layout: default
title: dates
---

date list 

{% for date in site.data.dates %}
<p>
{{ date.datum }}
<br>
{{ date.naam }}
</p>
{% endfor %}

