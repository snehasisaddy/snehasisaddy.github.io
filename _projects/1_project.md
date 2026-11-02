---
layout: page
title: Post-Processing for Quantum Key Distribution
description: Error correction and privacy amplification for QKD (M.Sc. project)
img: assets/img/AliceBob.drawio.jpg
importance: 4
category: academic
related_publications: false
---

After a quantum key exchange, Alice and Bob hold keys that differ by a few bit errors and that an eavesdropper may partly know. This project built the classical post-processing that turns them into one shared secret key: information reconciliation, which corrects the errors, and privacy amplification, which removes what an eavesdropper could have learned.

---

## Information reconciliation with polar codes

We developed the mathematics behind polar encoding, such as calculating Bhattacharyya parameters (BP) for binary symmetric channels, which are needed to build a reliability sequence. Using BP we developed the reliability-sequence algorithm, used it for polar encoding together with an existing polar decoder, and ran experiments to measure the performance of our encoder design.

- Developed an algorithm to find the reliability sequence required to perform encoding for arbitrarily long block length in a binary discrete memory-less channel.
- Implemented encoding of polar codes using the generated reliability sequence.
- Implemented decoding of polar codes using the successive-cancellation decoding method.
- Calculated the entropy loss and extractable key length.
- Studied working and design of polar codes.
- Worked with high-performance computer clusters.

The code for the reliability sequence is available <a href="https://github.com/snehasisaddy/reliabilityseq">here</a>.

## Information reconciliation with LDPC codes

We designed the LDPC encoder using a parity check matrix and the LDPC decoder using the Belief Propagation (BP) algorithm, and used them to perform error correction on an experimental QKD dataset.

- Designed an algorithm to find the parity check matrix needed to generate syndrome.
- Designed a complete interface to handle error correction (encoding and decoding) in a binary symmetric channel with different error rates.

## Privacy amplification

We designed a privacy amplification module for QKD.

- Designed a Toeplitz matrix as a universal hash function.
- Extracted a secret key from a weak secure key (key generated after error correction) using the Fast Fourier Transform (FFT) technique.

## References

Addy, S. (2024). Polar codes for information reconciliation in QKD Quantum security for polarized channels. Polar, 2024, 04-05.
