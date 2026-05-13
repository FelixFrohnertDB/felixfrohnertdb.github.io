---
layout: page
permalink: /publications/
title: Research
description:
nav: true
nav_order: 3
---

<!-- _pages/publications.md -->
<div class="research-page">
	<div class="publications">
		<h2 class="bibliography"><span></span></h2>
	</div>

	<h2>Current Projects</h2>
	<p>
		A snapshot of my ongoing research directions
	</p>

	<div class="row row-cols-1 row-cols-md-3">
		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/publication_preview/learningDFT.png"
					sizes="250px"
					alt="Permutation-equivariant molecular learning"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Permutation-Equivariant Molecules</h2>
					<p class="card-text">
						Learning molecular representations that respect permutation symmetries for
						stronger generalization and physically consistent prediction.
					</p>
				</div>
			</div>
		</div>

		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/buildingBlockLOAnsatzImproved.png"
					sizes="250px"
					alt="Inductive bias of parameterized quantum circuits"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Spectral Inductive Bias of Parameterized Quantum Circuits</h2>
					<p class="card-text">
						Studying how circuit structure shapes spectral expressivity, trainability,
						and the functions parameterized quantum models can learn.
					</p>
				</div>
			</div>
		</div>

		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/publication_preview/path.png"
					sizes="250px"
					alt="Reinforcement learning for quantum error correction"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Reinforcement Learning for Quantum Error Correction</h2>
					<p class="card-text">
						Training adaptive control and decoding policies that improve recovery
						strategies in noisy and fault-tolerant quantum settings.
					</p>
				</div>
			</div>
		</div>
	</div>

	<div class="mt-5">
		<h2>Published Projects</h2>
		<p>Selected published work and preprints.</p>
	</div>

	<div class="publications">
		{% bibliography %}
	</div>
</div>
