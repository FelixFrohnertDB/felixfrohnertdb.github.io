---
layout: page
title: Hackathon 
description: LOQCathon Paris
img: assets/img/Quandela.png
importance: 2
category: work
---

Hosted by Quandela $$\vert$$ Paris, France

LOQCathon was an interdisciplinary quantum hackathon focused on Linear Optical Quantum Computation (LOQC). Our challenge, “Unloqc the Energetics Properties of Molecules,” centered around implementing a Variational Quantum Eigensolver (VQE) to estimate ground state energies of molecules.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/buildingBlockLOAnsatzImproved.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Problem-inspired ansatz used in the Variational Quantum Eigensolver implementation on a linear optical quantum computer.
</div>

Our task was to develop and optimize a VQE using Perceval, Quandela's LOQC simulator, to compute upper bounds of the ground state energy for H₂O and LiH molecules. This involved:

- Designing hardware-efficient ansätze compatible with LOQC architectures

- Navigating expressivity–trainability trade-offs to avoid barren plateaus

- Benchmarking optimizers to achieve convergence

Our solution stood out for its performance, earning us the first place.

Further information can be found in the accompanying [GitHub repository](https://github.com/LOQCathon/unloqc-VQE-9).