---
title: "Secure puf-based authentication and key exchange protocol using machine learning"
collection: publications
category: conferences
permalink: /publication/PUFML
excerpt: 'This paper is about enabling secure, resilient and fast authentication and key exchange mechanism with PUF using machine learning.'
date: 2022.07.04
venue: 'ISVLSI 2022'
slidesurl: ''
paperurl: 'https://par.nsf.gov/servlets/purl/10356842'
citation: 'Ali-Pour, A., Afghah, F., Hely, D., Beroulle, V. and Di Natale, G., 2022, July. Secure puf-based authentication and key exchange protocol using machine learning. In 2022 IEEE Computer Society Annual Symposium on VLSI (ISVLSI) (pp. 386-389). IEEE.'
---

Profiling side-channel analysis has gained widespread acceptance in both
academic and industrial realms due to its robust capacity to unveil protected secrets,
even in the presence of countermeasures. To harness this capability, an adversary must
access a clone of the target device to acquire profiling measurements, labeling them
with leakage models. The challenge of finding an effective leakage model, especially
for a protected dataset with a low signal-to-noise ratio or weak correlation between
actual leakages and labels, often necessitates an intuitive engineering approach, as
otherwise, the attack will not perform well.
In this paper, we introduce a deep learning approach with a flexible leakage model,
referred to as the multi-bit model. Instead of trying to learn a pre-determined
representation of the target intermediate data, we utilize the concept of the stochastic
model to decompose the label into bits. Then, the deep learning model is used
to classify each bit independently. This versatile multi-bit model can adjust to
existing leakage models like the Hamming weight and Most Significant Bit while also
possessing the flexibility to adapt to complex leakage scenarios. To further improve
the attack efficiency, we extend the multi-bit model to profile all 16 subkey bytes
simultaneously, which requires negligible computational effort. The experimental
results show that the proposed methods can efficiently break all key bytes across four
considered datasets while the conventional leakage models fail. Our work signifies
a significant step forward in deep learning-based side-channel attacks, showcasing a
high degree of flexibility and efficiency with the proposed leakage model.