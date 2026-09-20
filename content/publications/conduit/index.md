---
title: 'CONDUIT: A Unified Residual-Stream Restoration Framework for KV Cache Reuse in Vision-Language Models'

authors:
  - Pengan Chen
  - admin
  - Liang Hong
  - Lixia Yi
  - Jiyue Jiang
  - Jiayang Chen
  - Yixuan Wang
  - Yimin Fan
  - Xinyuan Liu
  - Jiayi Li
  - Zhanqiu Zhang
  - Yiwen Guo
  - Yu Li

date: '2026-09-05T00:00:00Z'
publishDate: '2026-09-05T00:00:00Z'

publication_types: ['paper-conference']

publication:
  name: "Findings of the Association for Computational Linguistics: EMNLP 2026"
  short_name: "EMNLP Findings"

peer_reviewed: true
open_access: true

abstract: "Vision-language models (VLMs) often answer new questions about recurring visual content, where reusing the key-value (KV) cache can avoid re-encoding expensive visual prefixes. Exact-prefix reuse, however, fails when the same visual content appears under a changed prefix. Selective recomputation can recover quality under a small visual-token budget, but only when the right stale tokens are refreshed. Raw-attention selection can waste budget on high-attention tokens with small value-norm proxy scores and on query-irrelevant images. To address these failure modes, we propose CONDUIT, a training-free refresh policy that unifies single- and multi-image reuse as residual-stream restoration. Building on norm-weighted attention, CONDUIT ranks cached visual tokens using cached-key query attention and an accessible pre-output cached-value-norm proxy, then applies empirical image-level relevance amplification before one global selection. With one image, the coefficient is one and the rule reduces to intra-image token selection. The method preserves model architecture and weights, adding only a single query-conditioned scoring pass at inference. At a 10% refresh budget, CONDUIT achieves 97.0-99.5% of the corresponding full-prefill five-dataset average across three VLM backbones and leads budgeted methods on average; on the MMLongBench-Doc latency subset, it uses 13.5% of full-prefill FLOPs and achieves a 2.99x time-to-first-token speedup."

tags:
  - Vision-Language Models
  - KV Cache
  - Inference Optimization

featured: true

hugoblox:
  ids:
    arxiv: 2609.05821
    doi: 10.48550/arXiv.2609.05821

links:
  - type: preprint
    url: https://arxiv.org/abs/2609.05821
  - type: pdf
    url: https://arxiv.org/pdf/2609.05821

projects: []
slides: ""
---
