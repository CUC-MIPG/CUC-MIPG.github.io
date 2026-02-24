---
title: "News"
layout: textlay
excerpt: "M.L. Pacheco -- News"
sitemap: false
permalink: /allnews.html
---

## News

{% for article in site.data.news %}
#### {{ article.date }}
{% if article.link %}<a href="{{ article.link }}" target="_blank" rel="noopener noreferrer">{{ article.headline | markdownify | strip_html }}</a>{% else %}{{ article.headline | markdownify }}{% endif %}
{% endfor %}
