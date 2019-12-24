---
title: "Home"
layout: textlay
excerpt: "The Hydroinformatics Group at the University of Virginia."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<hr><p><em>{{ article.date }}</em>.
{{ article.headline }}</p>
{% endfor %}
