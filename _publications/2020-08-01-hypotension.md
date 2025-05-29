---
title: "Prediction of Hypotension Events with Physiologic Vital Sign Signatures in The Intensive Care Unit"
collection: publications
excerpt: '*Background*  
Even brief hypotension is associated with increased morbidity and mortality. We developed a machine learning model to predict the initial hypotension event among intensive care unit (ICU) patients and designed an alert system for bedside implementation.

*Materials and methods*  
From the Medical Information Mart for Intensive Care III (MIMIC-3) dataset, minute-by-minute vital signs were extracted. A hypotension event was defined as at least five measurements within a 10-min period of systolic blood pressure ≤ 90 mmHg and mean arterial pressure ≤ 60 mmHg. Using time series data from 30-min overlapping time windows, a random forest (RF) classifier was used to predict risk of hypotension every minute. Chronologically, the first half of extracted data was used to train the model, and the second half was used to validate the trained model. The model’s performance was measured with area under the receiver operating characteristic curve (AUROC) and area under the precision recall curve (AUPRC). Hypotension alerts were generated using risk score time series, a stacked RF model. A lockout time were applied for real-life implementation.

*Results*  
We identified 1307 subjects (1580 ICU stays) as the hypotension group and 1619 subjects (2279 ICU stays) as the non-hypotension group. The RF model showed AUROC of 0.93 and 0.88 at 15 and 60 min, respectively, before hypotension, and AUPRC of 0.77 at 60 min before. Risk score trajectories revealed 80% and > 60% of hypotension predicted at 15 and 60 min before the hypotension, respectively. The stacked model with 15-min lockout produced on average 0.79 alerts/subject/hour (sensitivity 92.4%).

*Conclusion*  
Clinically significant hypotension events in the ICU can be predicted at least 1 h before the initial hypotension episode. With a highly sensitive and reliable practical alert system, a vast majority of future hypotension could be captured, suggesting potential real-life utility.'
date: 2020-08-01
venue: 'Critical Care'
paperurl: 'https://ccforum.biomedcentral.com/articles/10.1186/s13054-020-03379-3'
citation: 'Yoon, J. H.*, Jeanselme, V.*, Dubrawski, A., Hravnak, M., Pinsky, M. R., Clermont, G. (2020). <b>Prediction of Hypotension Events with Physiologic Vital Sign Signatures in The Intensive Care Unit</b>. In <i>Critical Care, 24(1), 1-9</i>.'
---