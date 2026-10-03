---
title: dates
layout: page
picture-name: datesreyer.png
---

## where can I witness REYER?
{% for date in site.data.dates %}
<p class="future">
<b>{{ date.datum }} --- {{ date.naam }}</b><br>
{{ date.location }}
</p>
{% endfor %}

{% if site.data.pastdates.past[0] %}
{% for item in site.data.pastdates.past %}
<h3>{{ item.year }}</h3>
{% if item.performance[0] %}
{% for entry in item.performance %}
<b>{{ entry.performer }} --- {{ entry.work }}</b><br>
{{ entry.details }}
{% endfor %}
{% endif %}
{% endfor %}
{% endif %}