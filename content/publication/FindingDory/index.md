---
title: "FindingDory: A Benchmark to Evaluate Memory in Embodied Agents"

authors:
- admin
- Yusuf Ali
- Gunshi Gupta
- Yarin Gal
- Zsolt Kira

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2026-07-01T00:00:00Z"
doi: ""
publishDate: "2026-07-01T00:00:00Z"

publication_types: ["1"]
publication: In *European Conference on Computer Vision 2026*
publication_short: In *ECCV*

abstract: "Large vision-language models have recently demonstrated impressive performance in planning and control tasks, driving interest in their application to real-world robotics. However, deploying these models for reasoning in embodied contexts is limited by their ability to incorporate long-term experience collected across multiple days and represented by vast collections of images. Current VLMs typically struggle to process more than a few hundred images concurrently, highlighting the need for more efficient mechanisms to handle long-term memory in embodied settings. To effectively evaluate these models for long-horizon control, a benchmark must specifically target scenarios where memory is crucial for success. Existing long-video QA benchmarks overlook embodied challenges like object manipulation and navigation, which demand low-level skills and fine-grained reasoning over past interactions. Moreover, effective memory integration in embodied agents involves both recalling relevant historical information and executing actions based on that information, making it essential to study these aspects together rather than in isolation. In this work, we introduce a new benchmark for long-range embodied tasks in the Habitat simulator. This benchmark evaluates memory-based capabilities across 60 tasks requiring sustained engagement and contextual awareness in an environment. The tasks can also be procedurally extended to longer and more challenging versions, enabling scalable evaluation of memory and reasoning. We also present baselines that integrate state-of-the-art VLMs with low level navigation policies, assessing their performance on these memory-intensive tasks and highlight areas for improvement."
summary: FindingDory evaluates long-range memory and reasoning in embodied agents.

tags:
- Embodied AI
- Memory
- Benchmark

featured: false

links:
- name: Training Code
  url: 'https://github.com/findingdory-benchmark/findingdory-train'
- name: Finetuned Model
  url: 'https://huggingface.co/yali30/findingdory-qwen2.5-VL-3B-finetuned'
url_pdf: 'https://arxiv.org/pdf/2506.15635.pdf'
url_code: 'https://github.com/findingdory-benchmark/findingdory-habitat'
url_dataset: 'https://huggingface.co/datasets/yali30/findingdory'
url_poster: ''
url_project: 'https://findingdory-benchmark.github.io/'
url_slides: ''
url_source: 'https://arxiv.org/abs/2506.15635'
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
