---
title: "Let's Think in Two Steps: Mitigating Agreement Bias in MLLMs with Self-Grounded Verification"

authors:
- Moises Andrade
- Joonhyuk Cha
- Brandon Ho
- Vriksha Srihari
- admin
- Zsolt Kira

date: "2026-04-01T00:00:00Z"
doi: ""
publishDate: "2026-04-01T00:00:00Z"

publication_types: ["1"]
publication: In *International Conference on Learning Representations 2026*
publication_short: In *ICLR*

abstract: "Verifiers--functions assigning rewards to agent behavior--have been key to AI progress in math, code, and games. However, extending gains to domains without clear-cut success criteria remains a challenge: while humans can recognize desired outcomes, translating this intuition into scalable rules is nontrivial. Multimodal LLMs (MLLMs) offer a promising solution, given their world knowledge, human-preference alignment, and reasoning capabilities. We evaluate MLLM verifiers across web navigation, computer use, and robotics, spanning 13+ models, 28+ designs, and thousands of trajectories from diverse agents. We identify a critical limitation: a strong tendency for MLLMs to over-validate agent behavior--a phenomenon we term agreement bias. This bias is pervasive, resilient to test-time scaling, and can harm applications relying on MLLM judgments/rewards (e.g., self-improvement, steering, online supervision). We discuss several considerations for evaluating and designing MLLM verifiers, and introduce SGV, a lightweight method that better leverages their capabilities by modulating (un)conditional generation. First, an MLLM is elicited to generate broad priors about desired behavior, independent of the data under evaluation. Then, conditioned on self-generated priors, it reasons over and evaluates a candidate trajectory. Our methods yield more human-aligned verifiers, improving failure detection by 25pp and accuracy by 14pp. In self-improvement and online supervision, they boost task completion of a GUI specialist in OSWorld, a diffusion policy in robomimic, and a ReAct agent in VisualWebArena--surpassing the previous state of the art by 20pp. As a byproduct, we release an update of VisualWebArena featuring strong agent baselines, more human-aligned oracles, container parallelism with high fidelity and proper resets, >10x speedups, and VWA-Lite, a 1/3 subset with comparable evaluation fidelity."
summary: Self-Grounded Verification mitigates agreement bias in MLLM verifiers for web navigation, computer use, and robotic manipulation.

tags:
- Multimodal LLMs
- Verification
- Embodied AI

featured: false

links:
- name: Agent Reward Bench
  url: 'https://agent-reward-bench.github.io/'
url_pdf: 'https://arxiv.org/pdf/2507.11662.pdf'
url_code: 'https://github.com/mshalimay/mllm-verifiers-abias-sgv'
url_dataset: 'https://drive.google.com/drive/folders/15nAWNkyo6Jhsxl6RZg8cFRS_6jP-Xr-H'
url_poster: ''
url_project: 'https://mshalimay.github.io/agreement-bias-sgv/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2507.11662'
url_video: ''

image:
  caption: ''
  focal_point: ""
  preview_only: false

projects:
---

{{% callout note %}}
Click the *Cite* button above to view the bibtex.
{{% /callout %}}
