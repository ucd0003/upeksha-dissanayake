---
layout: page
title: Effects of Cancer Mutations on DNA Glycosylase (MUTYH)
description: This project investigates how cancer-associated mutations alter the structural stability, dynamics, and allosteric communication networks of the MUTYH DNA repair enzyme.
img: assets/img/MUTYH1.png
importance: 2
category: work
giscus_comments: false
---

MUTYH is a clinically important DNA glycosylase that thwarts mutations by initiating base-excision repair at 8-oxoguanine (OG):A lesions. The roles for its [4Fe-4S] cofactor in DNA repair remain enigmatic. Functional profiling of cancer-associated variants near the [4Fe-4S] cofactor reveals that most variations abrogate both retention of the cofactor and enzyme activity. Surprisingly, R241Q and N238S retained the metal cluster and bound substrate DNA tightly, but were completely inactive. We determine the crystal structure of human MUTYH bound to a transition state mimic and this shows that Arg241 and Asn238 build an H-bond network connecting the [4Fe-4S] cluster to the catalytic Asp236 that mediates base excision. The structure of the bacterial MutY variant R149Q, along with molecular dynamics simulations of the human enzyme, support a model in which the cofactor functions to position and activate the catalytic Asp. These results suggest that allosteric cross-talk between the DNA binding [4Fe-4S] cofactor and the base excision site of MUTYH regulate its DNA repair function.

<div class="row">
    <div class="col-md-6 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/MUTYH1.png" title="MUTYH structural model" class="img-fluid rounded z-depth-1" %}
</div>

    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
           path="assets/img/MUTYH.png"
           title="Active site interaction analysis"
           class="img-fluid rounded z-depth-1" %}
    </div>

</div>
  <div class="caption">
    Structural representation of human MUTYH bound to DNA, highlighting the active site pocket and key catalytic residues. The [4Fe–4S] cluster and Zn ion are shown as cofactors. Cancer mutations are R241Q and N238S
  </div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MUTYH-all.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Energy decomposition (left), normal mode (middle), and network (right) analyses based on the MD trajectories are shown
</div>

MD simulations were performed with AMBER to investigate the structural and dynamic relationships between the [4Fe-4S] cluster and the active site in the WT, R241Q and N238S mutant in both mouse and human homologs. 

We performed energy decomposition analysis (EDA) to quantify non-bonded interactions within the allosteric network linking the [4Fe–4S] cluster, catalytic Asp236, and the AP site. In the WT enzyme, Arg241 and Asn238 strongly stabilize the system, but mutations (R241Q and N238S) significantly weaken overall interactions. Notably, R241Q drastically reduces stabilizing interactions with Asp236 and the AP site, disrupting catalytic coupling. Both mutations decrease interaction strength between the [4Fe–4S] cluster and the protein, indicating reduced structural stability.

Dynamic network analysis further reveals that in the WT enzyme, Arg241 forms a key communication bridge between the [4Fe–4S] cluster and the AP site. This optimal allosteric pathway is altered or completely rerouted in the mutant systems. Overall, the simulations support the presence of a metal-centered allosteric network that regulates catalytic activity and substrate specificity in MUTYH.

<div class="row">
  <div class="col-md-6 mt-3">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline controls preload="metadata">
      <source src="{{ '/assets/video/MUTYH-NMA_web.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="caption">Normal-mode animation (MUTYH)</div>


{% raw %}


{% endraw %}
