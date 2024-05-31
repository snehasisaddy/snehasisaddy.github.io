---
layout: page
title: Information Reconciliation in QKD using Polar Codes
description: M.Sc. project
img: assets/img/AliceBob.drawio.jpg
importance: 1
category: work
related_publications: false
---

 This project involved the development of required mathematics such as calculating Bhattacharyya parameters (BP) for binary symmetric channels. Calculations of such parameters are necessary for the realization of a reliability sequence. Using BP we developed the algorithm for the reliability sequence which is necessary for encoding in polar codes. We later used this algorithm for polar encoding and an already available polar decoder to perform some experiments to determine the performance of our encoder design.

---
 Some highlights of the project are:
 - Developed an algorithm to find the reliability sequence required to perform encoding for arbitrarily long block length in a binary discrete memory-less channel.
 - Implemented encoding of polar codes using the generated reliability sequence.
 - Implemented decoding of polar codes using the successive-cancellation decoding method.
 - Calculated the entropy loss and extractable key length.
 - Studied working and design of polar codes.
 - Worked with high-performance computer clusters.

---

The code for the reliability sequence has been released and can be found  <a href="https://github.com/snehasisaddy/reliabilityseq"> here</a>.

## References
Addy, S. (2024). Polar codes for information reconciliation in QKD Quantum security for polarized channels. Polar, 2024, 04-05.
