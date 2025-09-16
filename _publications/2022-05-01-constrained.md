---
title: "Constrained clustering and multiple kernel learning without pairwise constraint relaxation"
collection: publications
excerpt: ''
date: 2022-05-01
venue: 'Springer - Advances in Data Analysis and Classification'
paperurl: 'https://doi.org/10.1007/s11634-022-00507-5'
citation: 'Boecking, B., Jeanselme, V., Dubrawski, A (2022). <b>Constrained clustering and multiple kernel learning without pairwise constraint relaxation</b>. In <i>Advances in Data Analysis and Classification, 1-16</i>.'
---
Clustering under pairwise constraints is an important knowledge discovery tool that enables the learning of appropriate kernels or distance metrics to improve clustering performance. These pairwise constraints, which come in the form of must-link and cannot-link pairs, arise naturally in many applications and are intuitive for users to provide. However, the common practice of relaxing discrete constraints to a continuous domain to ease optimization when learning kernels or metrics can harm generalization, as information which only encodes linkage is transformed to informing distances. We introduce a new constrained clustering algorithm that jointly clusters data and learns a kernel in accordance with the available pairwise constraints. To generalize well, our method is designed to maximize constraint satisfaction without relaxing pairwise constraints to a continuous domain where they inform distances. We show that the proposed method outperforms existing approaches on a large number of diverse publicly available datasets, and we discuss how our method can scale to handling large data.


Code available on [GitHub](https://github.com/autonlab/constrained-clustering).