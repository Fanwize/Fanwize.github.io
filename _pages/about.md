---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
layout: single
classes: wide
---

<!-- ====================================================================== -->
<!--                                 NEWS                                   -->
<!-- ====================================================================== -->
## News
<div class="news-entry">
  <span class="news-date">[Aug 2024]</span> I am thrilled to be joining the <a href="https://www.grasp.upenn.edu/" target="_blank">GRASP Laboratory</a> at the <b>University of Pennsylvania</b> as a visiting research student for the Fall 2024 semester.
  <br>
  I will be working on a project in 3D Physics under the supervision of <a href="https://lingjie0206.github.io/" target="_blank">Prof. Lingjie Liu</a>, and will be directly collaborating with Ph.D. student <a href="https://vlongle.github.io/" target="_blank">Long Le</a>.
</div>

---

<!-- ====================================================================== -->
<!--                               ABOUT ME                                 -->
<!-- ====================================================================== -->
## About Me
I am a final-year undergraduate student in Computer Science at the Southern University of Science and Technology (SUSTech), currently advised by **[Prof. Feng Zheng](https://faculty.sustech.edu.cn/zhengf/)**. <!-- 别忘了替换成你导师的主页链接 -->

My research goal is to enable machines to perceive, reason about, and interact with the 3D world as humans do. I am actively seeking a Ph.D. position for Fall 2026 and am passionate about building the next generation of intelligent systems.

---

<!-- ====================================================================== -->
<!--                           RESEARCH INTERESTS                           -->
<!-- ====================================================================== -->
## Research Interests
*   **Structured 3D Visual Reasoning:** Building interpretable models like Neural Module Networks (NMNs) for complex tasks such as 3D Visual Question Answering (VQA).
*   **Physics-Informed 3D AI:** Integrating physical principles into deep learning models to enable realistic and predictive understanding of object interactions and dynamics.
*   **Multimodal Learning:** Fusing vision, language, and other modalities to create robust and generalizable foundation models for 3D understanding.

---

<!-- ====================================================================== -->
<!--                              PUBLICATIONS                              -->
<!-- ====================================================================== -->
<h2 id="publications">Publications</h2>
{% for post in site.publications reversed %}
{% include card-entry.html %}
{% endfor %}

---

<!-- ====================================================================== -->
<!--                          RESEARCH EXPERIENCE                           -->
<!-- ====================================================================== -->
<h2 id="research">Research Experience</h2>
{% for post in site.research reversed %}
{% include card-entry.html %}
{% endfor %}

---

<!-- ====================================================================== -->
<!--                                EDUCATION                               -->
<!-- ====================================================================== -->
## Education
*   **Southern University of Science and Technology (SUSTech)**, Shenzhen, China
    *   *Bachelor of Science in Computer Science*, Sep. 2022 – Jun. 2026 (Expected)
    *   GPA: 3.89/4.00 (Rank: 14/162)

*   **National University of Singapore (NUS)**, Singapore
    *   *Summer Workshop in Computer Vision*, May 2024 – Jul. 2024
    *   Grade: A+