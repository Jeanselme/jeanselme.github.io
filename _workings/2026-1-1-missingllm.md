---
title: "Aligning Probabilistic Beliefs under Informative Missingness: LLM Steerability in Clinical Reasoning"
collection: workings
excerpt: "Large Language Models (LLMs) are increasingly deployed for clinical reasoning tasks, which inherently require eliciting calibrated probabilistic beliefs based on available evidence. However, real-world clinical data are frequently incomplete, with missingness patterns often informative of patient prognosis; for example, ordering a rare laboratory test reflects a clinician's latent suspicion. In this work, we investigate whether LLMs can be steered to leverage this informative missingness for prognostic inference. To evaluate how well LLMs align their verbalized probabilistic beliefs with an underlying target distribution, we analyze three common prompt-based interventions: explicit serialization, instruction steering, and in-context learning. We introduce a bias-variance decomposition of the log-loss to clarify the mechanisms driving gains in predictive performance. Using a real-world intensive care testbed, we find that while explicit structural steering and in-context learning can improve probabilistic alignment, the models do not natively leverage informative missingness without careful interventions."
date: 2026-1-1
venue: 'UAI'
paperurl: 'https://arxiv.org/abs/2512.00479'
citation: 'Kobayashi, Y., Jeanselme, V., and Joshi, S. <b>Aligning Probabilistic Beliefs under Informative Missingness: LLM Steerability in Clinical Reasoning</b>.'
---