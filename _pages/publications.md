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
		A snapshot of my ongoing research directions.
	</p>

	<div class="row row-cols-1 row-cols-md-3">
		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/topic1.png"
					sizes="250px"
					alt="Permutation-equivariant molecular learning"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Permutation-Equivariant Molecules</h2>
					<p class="card-text">
						Building symmetry-aware surrogate models that respect permutation structure, remain scale-invariant, and provide reliable predictions for strongly correlated molecular systems.

					</p>
				</div>
			</div>
		</div>

		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/topic2.png"
					sizes="250px"
					alt="Inductive bias of parameterized quantum circuits"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Inductive Bias of Quantum Circuits</h2>
					<p class="card-text">
						Studying how the spectral inductive bias of parameterized quantum circuits can be leveraged in machine learning tasks, and how it shapes trainability, expressivity, and generalization.
					</p>
				</div>
			</div>
		</div>

		<div class="col">
			<div class="card h-100 hoverable">
				{%
					include figure.liquid
					loading="eager"
					path="assets/img/topic3.png"
					sizes="250px"
					alt="Reinforcement learning for error correction"
					class="card-img-top"
				%}
				<div class="card-body">
					<h2 class="card-title">Reinforcement Learning for Error Correction</h2>
					<p class="card-text">
						 Developing reinforcement learning agents that adaptively reweight quantum error correction decoding graphs, improving logical error rates under realistic drift noise in surface code systems.
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
