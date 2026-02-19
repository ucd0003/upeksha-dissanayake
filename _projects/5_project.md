---
layout: page
title: Understanding mechanisms of non-contacting/non-interfacial mutations in protein-protein compensations
description: This project investigates how distant, non-contacting mutations modulate protein–protein interactions through long-range allosteric communication and compensatory network effects.
img: assets/img/ATT1.png
importance: 3
category: fun
related_publications: true
---

The ParE3–ParD3 toxin–antitoxin complex is a bacterial protein–protein interaction system where functional balance is tightly regulated. While many compensatory mutations occur at direct binding interfaces, this project focuses on non-contacting (distal) mutations that restore function through long-range structural and dynamic effects.

Using molecular dynamics (MD) simulations, we characterized how single and double mutations alter conformational flexibility, inter-residue communication, and binding stability within the complex. A deep suppressor scan identified compensatory toxin–antitoxin mutant pairs that restore cellular growth despite deleterious individual mutations.

To uncover the underlying mechanisms, we extracted MD-derived features—including RMSF, hydrogen bonding patterns, residue interaction networks, and dynamic cross-correlations—and trained a machine learning model to distinguish compensatory from non-compensatory mutant pairs. This integrative MD + ML framework reveals how distal mutations propagate through allosteric networks to re-establish functional protein–protein interactions.

Together, this study provides mechanistic insight into long-range mutation compensation and advances predictive modeling of protein–protein interaction resilience.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/ATT3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ATT2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

