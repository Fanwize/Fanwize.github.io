---
layout: career
title: Earlier Projects
description: "Earlier research and coursework by Qilin Huang in 3D visual reasoning, visual computing, and GPU programming."
permalink: /projects/earlier/
redirect_from:
  - /portfolio/
---

Earlier research and coursework in 3D visual reasoning, visual computing, and GPU programming.

<div class="earlier-projects">
  {% assign earlier_projects = site.research | concat: site.portfolio | where_exp: 'work', 'work.earlier_order != nil' | sort: 'earlier_order' %}
  {% for work in earlier_projects %}{% include earlier-project.html work=work %}{% endfor %}
</div>
