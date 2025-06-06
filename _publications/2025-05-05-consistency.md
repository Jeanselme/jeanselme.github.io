---
title: "Leveraging Expert Consistency to Improve Algorithmic Decision Support"
collection: publications
excerpt: 'Machine learning (ML) is increasingly being used to support high-stakes decisions, a trend owed in part to its promise of superior predictive power relative to human assessment. However, there is frequently a gap between decision objectives and what is captured in the observed outcomes used as labels to train ML models. As a result, machine learning models may fail to capture important dimensions of decision criteria, hampering their utility for decision support. In this work, we explore the use of historical expert decisions as a rich -- yet imperfect -- source of information that is commonly available in organizational information systems, and show that it can be leveraged to bridge the gap between decision objectives and algorithm objectives. We consider the problem of estimating expert consistency indirectly when each case in the data is assessed by a single expert, and propose influence function-based methodology as a solution to this problem. We then incorporate the estimated expert consistency into a predictive model through a training-time label amalgamation approach. This approach allows ML models to learn from experts when there is inferred expert consistency, and from observed labels otherwise. We also propose alternative ways of leveraging inferred consistency via hybrid and deferral models. In our empirical evaluation, focused on the context of child maltreatment hotline screenings, we show that (1) there are high-risk cases whose risk is considered by the experts but not wholly captured in the target labels used to train a deployed model, and (2) the proposed approach significantly improves precision for these cases.


Code available on [GitHub](https://github.com/mariadea/influence-labelers).'
date: 2025-05-05
venue: 'Management Science'
paperurl: 'https://pubsonline.informs.org/doi/full/10.1287/mnsc.2022.01576'
citation: 'De-Arteaga, M., Jeanselme, V., Dubrawski, A., Chouldechova, A. <b>Leveraging Expert Consistency to Improve Algorithmic Decision Support</b>. In <i>Management Science</i>.'
---