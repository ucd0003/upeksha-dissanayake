---
layout: page
title: Effect of Cancer Mutations on DNA Glycosylase (MUTYH)
#description: a project with a background image and giscus comments
img: assets/img/MUTYH1.png
importance: 2
category: work
giscus_comments: true
---

MUTYH is a clinically important DNA glycosylase that thwarts mutations by initiating base-excision repair at 8-oxoguanine (OG):A lesions. The roles for its [4Fe-4S] cofactor in DNA repair remain enigmatic. Functional profiling of cancer-associated variants near the [4Fe-4S] cofactor reveals that most variations abrogate both retention of the cofactor and enzyme activity. Surprisingly, R241Q and N238S retained the metal cluster and bound substrate DNA tightly, but were completely inactive. We determine the crystal structure of human MUTYH bound to a transition state mimic and this shows that Arg241 and Asn238 build an H-bond network connecting the [4Fe-4S] cluster to the catalytic Asp236 that mediates base excision. The structure of the bacterial MutY variant R149Q, along with molecular dynamics simulations of the human enzyme, support a model in which the cofactor functions to position and activate the catalytic Asp. These results suggest that allosteric cross-talk between the DNA binding [4Fe-4S] cofactor and the base excision site of MUTYH regulate its DNA repair function.


  <div class="row">
    <div class="col-md-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager"
           path="assets/img/MUTYH1.png"
           title="MUTYH structural model"
           class="img-fluid rounded z-depth-1" %}
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
    image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row">
  <div class="col-md-6 mt-3">
    <video class="img-fluid rounded z-depth-1" autoplay loop muted playsinline controls preload="metadata">
      <source src="{{ '/assets/video/MUTYH-NMA_web.mp4' | relative_url }}" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <div class="caption">Normal-mode animation (MUTYH)</div>
  </div>

    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
