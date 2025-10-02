---
layout: page
title: PULSE
description: Prototype-Guided Learning of Temporal CSI Features for Few-Shot Activity Recognition
img: assets/img/Pulse_Framework.jpg
importance: 1
category: Research
---

We present PULSE, a lightweight pipeline for activity recognition from Wi-Fi CSI. From real-world cap-
tures we form three physics-guided inter-frame descriptors—real-part correlation, complex Euclidean change, and
frame energy—over short windows; a compact 1D-CNN learns 128-D embeddings.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/Pulse_Framework.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Workflow of PULSE
</div>

----


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/high_activity.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Temporal Evolution of CFR with Change in Activities
</div>

To adapt across environments, we use training-free few-shot prototypes in cosine space built from only K labeled target windows. Two plug-in
normalizers—Support-Stat Adaptive Normalization and Prototype Fusion—further improve robustness, and an optional conformal rejection provides calibrated “unknown” decisions. On our real world CSI data PULSE achieves 98.9% in domain accuracy; with K=5 it attains 99.7% known-class accuracy without fine-tuning. PULSE is compute-efficient, requires no per-environment retraining, and offers a clear LOEO protocol for reproducible few-shot RF sensing.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cnn_tsne.png.png" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
   Clustered Activity Classes
</div>



