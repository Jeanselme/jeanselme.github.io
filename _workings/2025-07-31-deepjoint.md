---
title: "Prediction of Survival Outcomes under Clinical Presence Shift: A Joint Neural Network Architecture"
collection: workings
excerpt: "Electronic health records arise from the complex interaction between patients and the healthcare system. 
This observation process of interactions, referred to as clinical presence, often impacts observed outcomes. 
When using electronic health records to develop clinical prediction models, it is standard practice to overlook clinical presence, impacting performance and limiting the transportability of models when this interaction evolves.
We propose a multi-task recurrent neural network that jointly models the inter-observation time and the missingness processes characterising this interaction in parallel to the survival outcome of interest. 
Our work formalises the concept of clinical presence shift when the prediction model is deployed in new settings (e.g. different hospitals, regions or countries), and we theoretically justify why the proposed joint modelling can improve transportability under changes in clinical presence. 
We demonstrate, in a real-world mortality prediction task in the MIMIC-III dataset, how the proposed strategy improves performance and transportability compared to state-of-the-art prediction models that do not incorporate the observation process. 
These results emphasise the importance of leveraging clinical presence to improve performance and create more transportable clinical prediction models. "
date: 2025-07-31
venue: 'Lifetime Data Analysis'
paperurl: ''
citation: 'Jeanselme, V., Martin, G., Peek, N., Sperrin, M., Tom, B., Barrett, J. <b>Prediction of Survival Outcomes under Clinical Presence Shift: A Joint Neural Network Architecture</b>.'
---