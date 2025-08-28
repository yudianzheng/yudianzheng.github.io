---
permalink: /
title: "About Me/Planning"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Navigating the Academic Landscape as a Newcomer

### My Academic Path

I completed my undergraduate studies at the [University of Macau](https://www.um.edu.mo/), majoring in Computer Science. During my master’s program of Visual Computing at [Universität des Saarlandes](https://www.uni-saarland.de/), I worked on extending research in [Regression-based Monte Carlo Integration](https://arxiv.org/pdf/2211.07422), under the supervision of [Qinqin Hua](https://qingqin-hua.com/) and [Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html). Currently, I return to the [University of Macau](https://www.um.edu.mo/) to pursue my PhD, supervised by [Prof. Xiaodong Cun](https://vinthony.github.io/academic/) and [Prof. Chi-Man PUN](https://cmpun.github.io/). My research now focuses on 3D Vision (3DV) and its applications in the field of AIGC.

### Research Interests

As I outlined in My Academic Path, I have hands-on experience with both Physically Based Rendering (PBR) and Artificial Intelligence Generated Content (AIGC)—two areas that, despite their relevance to my research, differ fundamentally in their core logic.
PBR leans heavily into theoretical rigor: it relies on strict mathematical reasoning to model and describe the physical world objectively. The results it produces are, to a certain extent, unbiased, robust, and highly compressed—each formula and algorithm distills complex real-world phenomena into precise, interpretable rules. In contrast, AIGC (along with the 3D Vision backbones I now work with) is deeply data-driven. It excels at reshaping data to mirror the distributions of the real world, enabling the generation of complex scenes that would be extremely difficult to capture through theoretical modeling alone. Yet this strength comes with tradeoffs: data-driven outputs are often biased (shaped by the limitations of training datasets), suboptimal (trained to approximate rather than perfectly replicate reality), and redundant (carrying noise or unnecessary details from raw data).
What fascinates me most is this contrast between human and machine reasoning. As humans—agents that operate in parallel with deep learning systems—we can distill vast amounts of data into concise, theoretical conclusions: we observe patterns, derive principles, and compress complexity into actionable knowledge. The question that drives my research, then, is this: How can we equip deep learning systems with a similar ability? Bridging the gap between PBR’s theoretical precision and AIGC’s data-driven flexibility—teaching AI to “learn to compress” and “reason like humans” while retaining its power to generate complex content—feels like one of the most compelling and impactful challenges in my field today.

I am interested in visual representation methods. Currently, real-world visual information is usually represented with pixels as the smallest unit. However, this approach leads to significant information redundancy and inefficiency in processing.
To address this, models like Latent Diffusion Models map visual data to latent spaces, and NeRF also uses implicit representation. In contrast, formats such as SVG and 3D Gaussian Splatting (3DGS) are compressed explicit representations.
Different representation methods reduce information redundancy, enhance robustness, and facilitate various types of manipulation—for example, SVG is well-suited for editing. Exploring how to represent visual information and the advantages of different representations is one of my key areas of interest。

The second area of my interest is extending Physically Based Rendering (PBR) using large models. Traditional PBR faces significant limitations and has somewhat stagnated, for three key reasons:
First, modeling the real world is extremely challenging. Real-world scenes are highly complex, influenced by numerous factors, making it difficult to replicate them accurately.
Second, algorithm implementation is cumbersome. Even building a basic renderer requires addressing multiple aspects—including camera systems, geometry processing, material simulation, light sources, and rendering algorithms. Advanced algorithms like Bidirectional Path Tracing (BDPT) involve even more complex considerations, which are highly unfavorable for code implementation and maintenance.
Third, different rendering methods impose strict constraints on scenes: most are designed for specific scenarios and cannot guarantee a general improvement in rendering speed. Additionally, many of these algorithms are still optimized for CPUs, failing to fully leverage the parallel processing capabilities of modern hardware.
First, most large models adopt an end-to-end design paradigm, which simplifies both operation and maintenance logic—avoiding the cumbersome, modular coordination required by traditional PBR algorithms.
Second, large models are data-driven and trained on massive pre-validated data. This enables them to produce reliable results even in complex scenarios, implying significant potential for achieving general improvements in rendering performance (unlike traditional methods limited to specific use cases).
Third, large models are built on GPU architectures, which means they inherently possess strong parallel computing and scalability capabilities—addressing the inefficiency of traditional PBR algorithms that are often CPU-optimized and struggle to leverage parallel processing power.

At present, 3D Vision (3DV) is in a phase of dynamic development. The emergence of new backbones has demonstrated the feasibility of the scaling law in 3D domains—a breakthrough that makes 3D Vision far closer to capturing the "essence" of real-world objects and scenes than pure 2D vision. This shift also marks a gradual convergence of 3D Vision with Computer Graphics (CG), differing from the traditional focus of Computer Vision (CV).
On another front, advancing 3D Vision also offers substantial value for Artificial Intelligence Generated Content (AIGC): it provides critical support for a range of AIGC tasks, including video generation, 3D asset creation, and scene understanding. Importantly, we are still in the early stages of exploring and understanding the full potential of this synergy between 3D Vision and AIGC—leaving ample room for innovation and discovery.

### Evolving Research Perspectives

As time has passed, I've gradually formed coarse yet meaningful principles regarding research and learning, which now guide approach to my work:

1. Consistency: Scarce yet cultivable, it offers the most sustainable path to avoiding friction and leveraging energy long-term..

2. Time Management: Effective time management, rooted in holistic project understanding, delivers both efficient completion and the satisfaction of learning.

3. Idea > Achievement: While engineering is valuable, unique ideas are the true differentiator in research.

4. Learning by Doing: Ideas and practice are synergistic.

5. Designing Experiments: Effective experiments are simple, decomposable, and efficient.

6. Knowing When to “Think Hard”: Concentrate deep thinking on experiment design and result analysis. Avoid overcomplicating the experiment itself.