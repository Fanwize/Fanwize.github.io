---
layout: career
title: Sitemap
permalink: /sitemap/
---

- [Home]({{ '/' | relative_url }})
- [Publications]({{ '/publications/' | relative_url }})
- [Resume (PDF)]({{ site.career.resume.path | relative_url }})
- [Earlier projects]({{ '/projects/earlier/' | relative_url }})

## Research

{% for work in site.publications %}
- [{{ work.title }}]({{ work.url | relative_url }})
{% endfor %}
