---
permalink: /
layout: career
home: true
description: "Qilin Huang, CMU Computer Vision master's student. Controllable 3D physics and 3D visual question answering. Seeking Summer 2027 CV/ML internships."
redirect_from:
  - /about/
  - /about.html
---
<section class="profile" aria-labelledby="profile-title">
  <h1 id="profile-title">{{ site.name }}</h1>
  <p class="profile-affiliation">{{ site.career.degree }} · {{ site.career.institution }}</p>
  <p class="profile-graduation">Expected graduation: {{ site.career.graduation }} · {{ site.author.location }}</p>
  <p class="profile-intro">I am a master's student in Computer Vision at Carnegie Mellon University. My research includes controllable 3D physics and 3D visual question answering. I am a co-first author of <a href="#unipixie-title">UniPixie</a> (CVPR 2026 Highlight) and a co-author of <a href="#hcnqa-title">HCNQA</a> (ICANN 2025).</p>
  <p class="internship-target">{{ site.career.target }}</p>
  <div class="profile-links">
    {% include resume-link.html primary=true %}
    <a href="mailto:{{ site.author.email }}">Email</a>
    <a href="https://github.com/{{ site.author.github }}">GitHub</a>
  </div>
</section>

<section id="research" class="career-section" aria-labelledby="research-title">
  <span id="publications" class="anchor-alias" aria-hidden="true"></span>
  <h2 id="research-title">Selected Research</h2>
  {% assign selected = site.publications | where: 'selected', true | sort: 'selected_order' %}
  {% for work in selected %}{% include research-entry.html work=work %}{% endfor %}
  <p class="section-more"><a href="{{ '/publications/' | relative_url }}">All publications</a> · <a href="{{ '/projects/earlier/' | relative_url }}">Other Projects</a></p>
</section>

{% if site.career.skills.size > 0 %}
<section class="career-section" aria-labelledby="skills-title">
  <h2 id="skills-title">Technical Skills</h2>
  {% include technical-skills.html %}
</section>
{% endif %}

<section id="education" class="career-section" aria-labelledby="education-title">
  <h2 id="education-title">Education</h2>
  {% include education.html %}
</section>

<section id="contact" class="career-section" aria-labelledby="contact-title">
  <h2 id="contact-title">Contact</h2>
  <p>{{ site.career.target }}</p>
  <p><a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></p>
</section>
