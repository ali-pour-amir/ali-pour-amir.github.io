---
title: "Helper Data Masking for Physically Unclonable Function-Based Key Generation Algorithms"
collection: publications
category: manuscripts
permalink: /publication/helperdatamasking
excerpt: 'This paper is about how to secure the fuzzy extractor and error correction codes from adversaries who aim to enforce key values by manipulating the helper data. The paper proposes a countermeasure that masks the helper data to eliminate the efficacy of manipulation.'
date: 2022..
venue: 'IEEE Access'
slidesurl: ''
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9750135'
citation: 'Pour, A.A., Afghah, F., Hely, D., Beroulle, V., Di Natale, G., Korenda, A.R. and Cambou, B., 2022. Helper data masking for physically unclonable function-based key generation algorithms. IEEE Access, 10, pp.40150-40164.'
---

Key exchange protocols are a crucial part of the internet-based communication between connected devices in IoT. In this regard, Physically Unclonable Function (PUF) has been an enabler to provide intrinsic highly randomized source for key generation without requiring extra storage components. PUF however, is an unstable source. In that sense, Fuzzy Extractor (FE) methods with Error Correction Code (ECC) are used to ensure reliability of the key value. FE methods incorporate publicly available helper data to recreate an originally enrolled encryption key from the PUF in mission mode. It is crucial to ensure that the publicly available helper data leaks no valuable information from the source key value to allow untrusted parties to recreate the key. Here the adversary’s work is to modify the helper data to decrease the entropy of the recovered codes by the ECC, and push the communicating parties in generating the key that is known to the adversary as well. In this work, we propose to protect helper data via a PUF-based masking mechanism with variable positioning. Masking with variable positioning adds a new fold of complexity for the adversary which is capable to considerably increase the guessing entropy. Our experimental results show that for 256-bit helper data, a 16-bit mask value can increase the guessing entropy by 5 folds against a Reed Muller majority logic vote decoder. Moreover, we show that an increased number of masking such as 4 times a 16-bit masking, can increase the guessing entropy against the same Reed Muller decoding function by 20 folds.