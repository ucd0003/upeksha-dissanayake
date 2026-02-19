---
layout: page
title: Computational Characterization of the DNA Repair Mechanism 
description: This project is about studying DNA Repair mechanism of Primase-Polymerase C and initiation of DNA primer synthesis by CRISPR Associated Primase Polymerase (CAPP) enzymes 
img: assets/img/PrimPolC1.png
importance: 1
category: work
related_publications: false
---

DNA repair enzymes are essential for maintaining genomic integrity, yet the molecular details governing substrate recognition, conformational gating, and catalysis remain incompletely understood. This project focuses on the mechanistic and structural characterization of Primase-Polymerase C (PrimPol C), a DNA repair enzyme involved in primer synthesis and lesion bypass.

The pre-catalytic PrimPol C crystal structure contains two molecules in the asymmetric unit, revealing conformational heterogeneity within the active site. A key residue, Arg179 (R179), functions as a dynamic gate that adopts two distinct conformations:

Open conformation – permits entry of the incoming nucleotide into the active site

Closed conformation – stabilizes substrate positioning and facilitates catalysis

We hypothesize that this gating motion plays a central role in regulating substrate access, structural stability, and reaction progression.

To investigate this mechanism, we analyzed both pre-catalytic and post-catalytic two-nucleotide gap structures of PrimPol C. Using extensive all-atom Molecular Dynamics (MD) simulations with AMBER, we characterized conformational dynamics, residue interaction networks, and nucleotide positioning. Subsequently, hybrid Quantum Mechanics/Molecular Mechanics (QM/MM) calculations were performed to elucidate the chemical reaction mechanism and quantify energetic contributions associated with the gating residue.

This integrative computational approach reveals how R179 modulates structural dynamics and directly influences the catalytic landscape of DNA repair synthesis. The study provides atomistic insights into nucleotide incorporation fidelity and contributes to a broader understanding of DNA repair regulation in primase-polymerase enzymes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PrimPolC2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/PrimPolc3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1"
               autoplay loop muted playsinline controls>
            <source src="{{ '/assets/video/Primpolc-qm_web.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    On the left, a structural representation of R179 closed and open conformations. Middle, Energy Decomposition Analysis between R 179 open and closed conformations. Right, Reaction mechanism calculations for R179 closed and open calculations
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1"
               autoplay loop muted playsinline controls>
            <source src="{{ '/assets/video/Primpolc-nci_web.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    This represents how non covalent interactions and electron density changes in the active site along the reaction path   
</div>

CRISPR-associated primase-polymerases (CAPPs) initiate DNA primer synthesis during CRISPR-mediated adaptive immunity. Guided by recent structural studies (Nature, 2022), this project investigates the molecular mechanism of primer initiation and early extension at atomistic resolution.

I performed polarizable MD simulations using the AMOEBA force field in TINKER, including custom nucleotide parameterization, to compare two-metal (2 Mg²⁺) and three-metal (3 Mg²⁺) catalytic systems. The simulations reveal how metal stoichiometry influences active-site geometry, substrate positioning, and catalytic readiness.

Normal Mode Analysis shows limited protein flexibility, consistent with the thermophilic origin of this enzyme. Simulations at 300 K therefore exhibit reduced conformational fluctuations, reflecting the inherent structural rigidity of thermophilic systems.

Together, this work clarifies how metal coordination and protein dynamics regulate primer synthesis in CAPP. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Capp2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Capp3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <video class="img-fluid rounded z-depth-1"
               autoplay loop muted playsinline controls>
            <source src="{{ '/assets/video/CAPP-NMA_web.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    On the left, Overall structural representation of the CAPP enzyme. Middle, Active-site architecture comparing the two-metal (2 Mg²⁺) and three-metal (3 Mg²⁺) catalytic systems. Right, Normal Mode Analysis (NMA) illustrating the dynamic behavior of the two systems.
</div>

{% raw %}


{% endraw %}
