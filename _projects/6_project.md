---
layout: page
title: Distributed Transaction Server
description: Scalable fault-tolerant stock trading platform with Paxos consensus
img: assets/img/baran_distributed_network.svg
importance: 3
category: work
related_publications: false
---

Designed and implemented a scalable three-tier stock trading platform (Frontend, Backend — Catalog and Order services) capable of handling high user concurrency through a dynamic thread-pool scheduling model.

---
Some highlights of this project are:
- Achieved redundancy and fault tolerance via Bully Leader Election and Paxos-based consensus, ensuring consistent state synchronization across replicas under node failures.
- Enhanced frontend performance with an LRU caching layer that reduced latency for frequent stock lookup requests.
- Stress-tested the system under high concurrency to validate throughput and consistency guarantees.

---
*Advisor: <a href="https://people.cs.umass.edu/~shenoy/">Prof. Prashant Shenoy</a>, UMass Amherst.*

---
<small>Figure: <a href="https://commons.wikimedia.org/wiki/File:Baran_distributed_network_(2).svg">Baran distributed network</a> by Pr.mtb, <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a>, via Wikimedia Commons.</small>
