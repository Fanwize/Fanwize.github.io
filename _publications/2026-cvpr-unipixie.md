---
title: "UniPixie: Unified and Probabilistic 3D Physics Learning via Flow Matching"
short_title: UniPixie
collection: publications
category: conferences
year: 2026
venue: CVPR
recognition: Highlight
author_role: First Author
equal_contribution: true
selected: true
selected_order: 1
authors:
  - name: Qilin Huang
    equal: true
  - name: Quynh Anh Huynh
    equal: true
  - name: Long Le
    equal: true
  - name: Chen Wang
  - name: Chuhao Chen
  - name: Ryan Lucas
  - name: Eric Eaton
  - name: Lingjie Liu
research_context: "Research Project · GRASP Laboratory, University of Pennsylvania · Jul. 2025–Mar. 2026 · Philadelphia, PA / Remote"
overview: "UniPixie generates spatially varying material properties from visual features using conditional flow matching, with scalar conditioning for continuous stiffness control."
contribution: "I built the conditional flow-matching model and designed comparative experiments and ablations on PixieMultiVerse. I developed unified interfaces connecting model predictions to three existing simulation backends: Material Point Method, linear blend skinning, and spring-mass systems."
result: "On PixieMultiVerse, UniPixie achieved 55.6% lower MSE in log Young's modulus than retrained PIXIE."
description: "Controllable 3D material properties through flow matching. CVPR 2026 Highlight; first author Qilin Huang."
paperurl: https://arxiv.org/abs/2606.05399
projectpage: https://unipixie.github.io/
figure:
  path: /images/unipixie-teaser-640.webp
  srcset:
    - path: /images/unipixie-teaser-320.webp
      width: 320
    - path: /images/unipixie-teaser-640.webp
      width: 640
    - path: /images/unipixie-teaser-960.webp
      width: 960
  alt: "UniPixie alpha-controlled dynamics: basketball and duck examples in initial, soft, and stiff states."
  caption: "A single control varies material stiffness from soft to stiff."
  width: 640
  height: 491
---
