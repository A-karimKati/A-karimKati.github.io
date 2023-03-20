---
title: '<strong>Cryptanalysis Strikes Back, A Realistic assessment of leakage attacks on Encrypted Search</strong>'
collection: talks
type: 'tutorial'
permalink: /talks/aarhus
venue: "Aarhus Crypto Seminar"
date: 2022-01-24
location: "Aarhus University"
slidesurl: 'http://A-karimKati.github.io/files/aarhus.pdf'
---
[More information here](https://cs.au.dk/research/cryptography-and-security/seminar)

__Abstract:__
Motivated by the rapid rise in users reliance on third-party service providers, and the consistent increase in the frequency of privacy violations due to the inevitability of data breaches (data leaks), specifically among cloud providers that require access to plaintext data in order to process it, we believe that a broad deployment of Encrypted Search Algorithms (ESAs) is highly needed towards practical data security. 
ESAs are constructions that allow the users' to securely search over encrypted outsourced data, this capability comes with a complex tradeoffs between efficiency, expressiveness, and security. 
 
Concerning the security aspect, ESAs are characterized by leakage profiles modeling a set of leakage patterns. To assess how exploitable each profile can be under which assumptions, leakage attacks have been proposed. The attacks leverage leakage patterns with auxiliary knowledge to recover the content of private data and or queries. This represent a significant advances in our understanding of the impact and exploitability of leakage, which leads to increasingly lower errors given less information under more realistic assumptions.
 
Because much of ESAs research is theoretical, figuring out the impact of attacking a specific leakage profile in a practical real-world setting, i.e. large-scale data platform, presented a new open-challenge. First, we proposed a modular framework in order to open-source and re-evaluate state-of-the-art attacks and counter measures. Second, we depicted the different assumptions made over data and query distributions usually by prior works. An important aspect of our was based on assessing the effectiveness of leakage abuse attacks given these assumptions,, i.e. propose a clearer understanding of the prior assumptions in order to evaluate the attacks feasibility for large scale deployable solutions.