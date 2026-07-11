---
title: "Research"
hero_image: "hero.jpg"
nometadata: true
notags: true
noshare: true
nocomments: true
---

<h2>Research Experience</h2>

<h3>A Unified Two-Tier Architecture for PaddlePaddle — Baidu (Engineer)</h3>
<p><em>Mar 2025 – Aug 2025</em></p>
<p>Developed an exact-semantic, high-performance fusion architecture for the
PaddlePaddle AI compiler. Unlike traditional layered TVM-style compilers that
introduce semantic inconsistencies and backend inefficiencies, this solution uses
a unified two-tier design: the first layer abstracts backend index mutations and
folds their operations directly into fusion, while the second layer generates code
using topological information and affine transformations. Implemented a pass for
MatMul + linear operations and evaluated it on 200 subgraphs from large language
models, achieving an average 12% speedup over the Phi high-performance operator
library.</p>

<h3>Optimal Tiling Configuration Search Technique (Group Member)</h3>
<p><em>Mar 2024 – Jul 2024</em></p>
<p>Investigated a computational graph acceleration technique that automatically
adapts user code to backend GPUs, combining model abstraction, sliding-window input
range segmentation, optimal configuration search, and an efficiency equation. Tiling
optimizes memory allocation and thread-block parameters, reducing memory-access
conflicts and increasing parallelism. Achieved an average 22% speedup on popular
subgraphs, with a maximum boost of 580%.</p>

<h3>Finding Numerical Errors Introduced by Deep Learning Compilers (Head)</h3>
<p><em>Feb 2023 – Jan 2024</em></p>
<p>Proposed <strong>TracNe</strong> to detect and diagnose numerical deviations
introduced by deep learning compilers. It combines (1) a MEGA search method for
generating error-triggering inputs and (2) a semantic-based exact-match algorithm
for tracing deviations and locating root causes. Evaluation on two benchmarks
demonstrated its usefulness as a unit test for ensuring model robustness. Published
at ISSRE 2024.</p>

<h3>Protecting Recommendation Models Against Privacy Leakage (Head)</h3>
<p><em>Feb 2022 – Jun 2022</em></p>
<p>Designed a homomorphic-encryption training approach based on the CKKS algorithm
to mitigate privacy leakage in recommendation models. The approach reduced the number
of encryptions per iteration by 66% and lowered training overhead compared to prior
work. The project reached the finals of the Shanghai "Tianyi Cloud" Cup.</p>

<h3>Defense on Recommendation Models (Group Leader)</h3>
<p><em>Jan 2021 – Jun 2021</em></p>
<p>Focused on the model security of commercial recommendation systems, revealing
vulnerabilities and proposing an effective defense method that outperformed earlier
work on several defensive metrics.</p>

<h3>Alignment of Corpora on Low-Resource Languages (Group Member)</h3>
<p><em>Oct 2020 – Apr 2021</em></p>
<p>Developed an efficient low-resource language collection and an alignment algorithm
based on XLM-R, improving the BLEU score of machine translation for low-resource
languages by an average of 1.5%.</p>

<h3>Malware Detection on Millions of Data Points (Group Leader)</h3>
<p><em>Mar 2020 – Sept 2020</em></p>
<p>Addressed zero-day attacks that challenge signature-based malware detection by
combining access relationships with a Markov chain model, improving the recall of
malicious files to 97%.</p>

<h2>Selected Projects</h2>

<h3>GraphNet: A Large Benchmark for Tensor Compiler Optimization (Core Contributor)</h3>
<p><em>Mar 2025 – Aug 2025</em></p>
<p>Participated as an early core contributor in the development of GraphNet, a
large-scale dataset of deep learning computation graphs designed as a standard
benchmark for tensor compiler optimization. Implemented techniques to extract
computation subgraphs with diverse topological features from both PyTorch and
PaddlePaddle, and established a preliminary benchmark for cross-framework
comparison. See the
<a href="https://github.com/PaddlePaddle/GraphNet/blob/develop/GraphNet_technical_report.pdf">technical report</a>.</p>

<h3>Improving the Alibaba HALO Compiler (Group Member)</h3>
<p><em>May 2022 – Sept 2022</em></p>
<p>Added a subgraph-fusion optimization to Alibaba's HALO compiler, integrating four
types of neighboring compute operations into a single kernel. Combined with CUTLASS
optimization, this pass improved inference throughput by 18.3% over TVM.</p>

<h2>Skills</h2>

<p>C/C++, AI compilers &amp; frameworks, CUDA, NPU Ascend, MetaX.</p>
