---
title: "Aggregation and Transformation of Vector-Valued Messages in the Shuffle Model of Differential Privacy"
collection: publications
permalink: /publications/2022-01-28-aggregation.md
excerpt: 'In this work we improve the error bound produced by the previous research by implementing a Discrete Fourier Transform.'
date: 2022-01-28
venue: 'IEEE Transactions on Information Forensics and Security'
citation: 'Scott, Mary, Cormode, Graham and Maple Carsten (2022) Aggregation and Transformation of Vector-Valued Messages in the Shuffle Model of Differential Privacy. In: TIFS: IEEE Transactions on Information Forensics and Security pp. 612-627. ISSN 1556-6013. DOI: 10.1109/TIFS.2022.3147643.'
---

Advances in communications, storage and computational technology allow significant quantities of data to be collected and processed by distributed devices. Combining the information from these endpoints can realize significant societal benefit but presents challenges in protecting the privacy of individuals, especially important in an increasingly regulated world. Differential privacy (DP) is a technique that provides a rigorous and provable privacy guarantee for aggregation and release. The Shuffle Model for DP has been introduced to overcome challenges regarding the accuracy of local-DP algorithms and the privacy risks of central-DP. In this work we introduce a new protocol for vector aggregation in the context of the Shuffle Model. The aim of this paper is twofold; first, we provide a single message protocol for the summation of real vectors in the Shuffle Model, using advanced composition results. Secondly, we provide an improvement on the bound on the error achieved through using this protocol through the implementation of a Discrete Fourier Transform, thereby minimizing the initial error at the expense of the loss in accuracy through the transformation itself. This work will further the exploration of more sophisticated structures such as matrices and higher-dimensional tensors in this context, both of which are reliant on the functionality of the vector case.
