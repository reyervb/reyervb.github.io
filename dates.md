---
title: dates
footer_var: footer.html
---

<h1>{{ page.title }}</h1>

{% for date in site.data.dates %}
<p>
{{ date.datum }}
<br>
{{ date.naam }}
</p>
{% endfor %}

