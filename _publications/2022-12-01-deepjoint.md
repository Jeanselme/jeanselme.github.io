---
title: "DeepJoint: Robust Survival Modelling Under Clinical Presence Shift"
collection: publications
excerpt: 'Observational data in medicine arise as a result of the complex interaction between patients and the healthcare system. The sampling process is often highly irregular and itself constitutes an informative process. When using such data to develop prediction models, this phenomenon is often ignored, leading to sub-optimal performance and generalisability of models when practices evolve. We propose a multi-task recurrent neural network which models three clinical presence dimensions -- namely the longitudinal, the inter-observation and the missingness processes -- in parallel to the survival outcome. On a prediction task using MIMIC III laboratory tests, explicit modelling of these three processes showed improved performance in comparison to state-of-the-art predictive models (C-index at 1 day horizon: 0.878). More importantly, the proposed approach was more robust to change in the clinical presence setting, demonstrated by performance comparison between patients admitted on weekdays and weekends. This analysis demonstrates the importance of studying and leveraging clinical presence to improve performance and create more transportable clinical models.


Code available on [GitHub](https://github.com/Jeanselme/ClinicalPresence).'
date: 2022-12-01
venue: 'NeurIPS Workshop TS4H'
paperurl: 'https://arxiv.org/abs/2205.13481'
citation: 'Jeanselme, V., Martin, G., Peek, N., Sperrin, M., Tom, B., Barrett, J. (2022). <b>DeepJoint: Robust Survival Modelling Under Clinical Presence Shift </b>. In <i>NeurIPS 2022 Workshop on Learning from Time Series for Health</i>.'
---