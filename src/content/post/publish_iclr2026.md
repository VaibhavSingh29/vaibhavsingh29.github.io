---
title: "Paper titled 'Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents' accepted at ICLR 2026 Workshop MemAgents"
description: "Our paper on Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents was accepted at ICLR 2026 MemAgents Workshop."
publishDate: "3 Mar 2026"
tags: ["research", "publication"]
---

Our paper **Chow-Liu Ordering for Long-Context Reasoning in Chain-of-Agents** has been accepted as a workshop paper at the ICLR 2026 Workshop MemAgents.

Authors: Naman Gupta*, Vaibhav Singh*, Arun Iyer, Kirankumar Shiragur, Pratham Grover, Ramakrishna B. Bairi, Ritabrata Maiti, Sankarshan Damle

*Equal Contribution

Sequential multi-agent reasoning frameworks such as Chain-of-Agents (CoA) handle long-context queries by decomposing inputs into chunks and processing them sequentially using LLM-based worker agents that read from and update a bounded shared memory. From a probabilistic perspective, CoA aims to approximate the conditional distribution corresponding to a model capable of jointly reasoning over the entire long context. CoA achieves this through a latent-state factorization in which only bounded summaries of previously processed evidence are passed between agents. The resulting bounded-memory approximation introduces a lossy information bottleneck, making the final evidence state inherently dependent on the order in which chunks are processed.
In this work, we study the problem of chunk ordering for long-context reasoning. We use the well-known Chow-Liu trees to learn a dependency structure that prioritizes strongly related chunks. Empirically, we show that a breadth-first traversal of the resulting tree yields chunk orderings that reduce information loss across agents and consistently outperform both default document-chunk ordering and semantic score-based ordering in answer relevance and exact-match accuracy across three long-context benchmarks.

[arXiv](https://arxiv.org/abs/2603.09835)
