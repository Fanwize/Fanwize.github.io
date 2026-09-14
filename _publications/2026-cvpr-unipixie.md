---
title: "UniPixie: Unified and Probabilistic 3D Physics Learning via Flow Matching"
short_title: UniPixie
permalink: /publication/unipixie/
collection: publications
category: conferences
year: 2026
venue: CVPR
recognition: Highlight
author_role: Co-first author
equal_contribution: true
selected: true
selected_order: 1
project_title: "UniPixie: Controllable 3D Physics"
project_period: Jul. 2025 – Mar. 2026
project_affiliation: GRASP Laboratory, University of Pennsylvania
project_location: Philadelphia, PA / Remote
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
overview: "UniPixie infers spatially varying material properties from visual features using conditional flow matching, with scalar conditioning for continuous stiffness control."
contribution: "I built the conditional flow-matching model and designed comparative experiments and ablation studies. I developed unified interfaces connecting model predictions to three existing simulation backends: Material Point Method, linear blend skinning, and spring-mass systems."
result: "On PixieMultiVerse, UniPixie achieved 55.6% lower MSE in log Young's modulus than retrained PIXIE."
description: "Controllable 3D material properties through flow matching. CVPR 2026 Highlight; co-first author Qilin Huang."
paperurl: https://arxiv.org/abs/2606.05399
projectpage: https://unipixie.github.io/
---

## Research context

This work was conducted with the University of Pennsylvania's GRASP Laboratory, under the supervision of Prof. Lingjie Liu and in collaboration with Long Le and the co-authors listed above.

[Project context at UPenn]({{ '/research/2025-upenn-physics/' | relative_url }}).

## Evaluation context

The selected result refers to log Young's modulus MSE on PixieMultiVerse, compared with retrained PIXIE. The relative reduction applies to this metric, rather than every evaluation measure. See [Table 1 in the paper](https://arxiv.org/html/2606.05399v2) for the full comparison.
