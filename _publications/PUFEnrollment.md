---
title: "Strong puf enrollment with machine learning: A methodical approach"
collection: publications
category: manuscripts
permalink: /publication/PUFEnrollment
excerpt: 'This paper is about introducing a methodology for PUF enrollment which uses machine learning to enroll the PUF-enabled systems.'
date: 2022..
venue: 'MDPI Electronics'
slidesurl: ''
paperurl: 'https://www.mdpi.com/2079-9292/11/4/653'
citation: 'Ali-Pour, A., Hely, D., Beroulle, V. and Di Natale, G., 2022. Strong puf enrollment with machine learning: A methodical approach. Electronics, 11(4), p.653.'
---

Physically Unclonable Functions (PUFs) have become ubiquitous as part of the emerging cryptographic algorithms. Strong PUFs are also predominantly addressed as the suitable variant for lightweight device authentication and strong single-use key generation protocols. This variant of PUF can produce a very large number of device-specific unique identifiers (CRPs). Consequently, it is infeasible to store the entire CRP space of a strong PUF into a database. However, it is potential to use Machine Learning to provide an estimated model of strong PUF for enrollment. An estimated model of PUF is a compact solution for the designer’s community, which can provide access to the full CRP space of the PUF with some probability of erroneous behavior. To use this solution for enrollment, it is crucial on one hand to ensure that PUF is safe against a model-building attack. On the other hand, it is important to ensure that the ML-based enrollment will be performed efficiently. In this work, we discuss these factors, and we present a formalized procedure of ML-based modeling of PUF for enrollment. We first define a secure sketch which allows modelability of PUF only for a trusted party. We then highlight important parameters which constitute the cost of enrollment. We show how an ML-based enrollment procedure should use these parameters to evaluate the enrollment cost prior to enrolling a large group of PUF-enabled devices. We introduce several parameters as well to control ML-based modeling in favor of PUF enrollment with minimum cost. Our proposed ML-based enrollment procedure can be considered a starting point to develop enrollment solutions for protocols which use an estimated model of PUF instead of a CRP database. In the end, we present a use-case of our ML-based enrollment method to enroll 100 instances of 2-XOR Arbiter PUFs and discuss the evaluative outcomes.