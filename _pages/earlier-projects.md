---
layout: career
title: Other Projects
description: "Selected research and course projects in map-based visual localization, 3D visual reasoning, face recognition, and CPU/GPU computing."
permalink: /projects/earlier/
redirect_from:
  - /portfolio/
---

Selected research and course projects in map-based visual localization, 3D visual reasoning, face recognition, and CPU/GPU computing.

<div class="earlier-projects">
  {% assign earlier_projects = site.research | concat: site.portfolio | where_exp: 'work', 'work.earlier_order != nil' | sort: 'earlier_order' %}
  {% for work in earlier_projects %}{% include earlier-project.html work=work %}{% endfor %}
</div>
