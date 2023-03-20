---
title: '<strong>All about that Data: Towards a Practical Assessment of Attacks on Encrypted Search</strong>'
collection: talks
type: 'tutorial'
permalink: /talks/rwc22
venue: "Real World Crypto Symposium"
date: 2022-04-13
location: "Amsterdam, The Netherlands"
slidesurl: 'http://A-karimKati.github.io/files/rwc.pdf'
---
[More information here](https://rwc.iacr.org/2022/)

__Abstract:__
Motivated by calls for privacy and data breaches of cloud services, efforts to broadly deploy Encrypted Search Algorithms (ESAs) are moving forward. ESAs allow search on encrypted data and can be found in research as well as industry. As all practical solutions leak some information, cryptanalysis plays an important role in the area of encrypted search. Many attacks have been proposed that exploit different leakage profiles under various assumptions. While leakage attacks aim to improve our common understanding of leakage, it is difficult to draw definite conclusions about their practical risk. This uncertainty stems from many limitations including a lack of reproducibility due to closed-source implementations, empirical evaluations conducted on small and/or unrealistic data, and reliance on very strong assumptions that can significantly affect accuracy. Particularly, assumptions made about the query distribution do not have any empirical basis because datasets containing users' queries are hard to find.

In this talk, we present results from our extensive re-evaluation of leakage attacks on many new datasets in a variety of use cases that - for the first time - include query data. We show that in many of these cases the practical risk of leakage is not as expected. Moreover, the evaluations and conclusions of our work are far from final and still suffer from the fact that for increasingly practical studies of attacks more (especially query) data is desperately needed, which is largely unavailable to researchers. We therefore also cover the remaining challenges from both a research and an industry perspective towards practically assessing the security of ESAs to enable adequate deployments.
