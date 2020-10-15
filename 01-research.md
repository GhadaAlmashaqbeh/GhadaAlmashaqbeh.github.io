---
layout: page
title: Research
permalink: /research/
---


<h1 style="font-family: 'Comic Sans MS'">Research</h1>

My research interests span cryptography, computer systems security, and privacy. Broadly, I work on interdisciplinary projects that combine knowledge from various fields toward the design of secure systems and protocols. In my research, I look for real life problems and build solutions backed by rigorous theoretical foundations as well as efficient implementations and thorough performance testing. I am also interested in conceptual projects that contribute in bridging the gap between theory and practice of Cryptography. 
<br/>
<br/>


<h4 style="font-family: 'Comic Sans MS';color: slateblue;">Current Projects</h4>

* **Gage MPC:** Develop a new MPC model which circumvents the residual function lower bound on non-interactive MPC protocol (computing the functionality output on the honest parties inputs and all combinations of adversarial inputs), and enforces complete fairness (either all parties learn the output or no one does). The project utilizes a blockchain in a novel way, incorporating smart contracts and (arbitrary) miners as participants. Monetary incentivised time lock capsules are used to economically incentivize participants to evaluate the intended MPC functionality, otherwise, miners will do that while collecting the participants collateral as a reward. 


* **smartFHE:** Investigate the possibility of building privacy-preserving smart contract system that not only supports private payments, but also arbitrary computations over private data and accounts. The project aims to explore to what extent fully homomorphic encryption (which allow computation over encrypted data) combined with non-interactive zero knowledge proofs (to defend against malicious adversaries) can be utilized in achieving this goal.


* **Basing cryptography on biological polymers:** In stealthy mode :)
<br/>
<br/>


<h4 style="font-family: 'Comic Sans MS';color: slateblue;">Previous Projects</h4>

* **CacheCash:** A system that provides a decentralized content delivery network (CDN) service by forming a distributed bandwidth marketplace powered by a cryptocurrency. This project covered several components including a threat modeling framework for cryptocurrencies ([ABC, CryBlock 2019](https://ieeexplore.ieee.org/document/8845101)), a defense mechanism against cache accounting attacks in peer-assisted CDNs ([CAPnet, IEEE CNS 2019](https://ieeexplore.ieee.org/document/8802825)), a lightweight probabilistic micropayment scheme ([MicroCash, FC 2020](https://fc20.ifca.ai/preproceedings/38.pdf)), and CacheCash, the main system that integrates these modules into its design.


* **Privacy-preserving programming compiler extension:** Build the first framework to support pointers to private data for privacy preserving programming compilers. This involved extending the PICCO compiler to implement this framework, and studying the efficiency trade-offs of using pointers to private data in secure algorithms and protocols. Read about this framework in our [TOPS 2017](https://dl.acm.org/citation.cfm?id=3154600) paper.


* **Privacy-preserving genome testing:** Develop protocols that perform genome tests to detect gene mutations without revealing any information about the underlying genome sequences. This project was a submission to the 4th [iDash Privacy & Security Workshop](http://www.humangenomeprivacy.org/2015/) competition. Read about these protocols in our [BMC 2015](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/1472-6947-15-S5-S4) paper.
