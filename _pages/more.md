---
permalink: /more/
title: "More"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

### My Academic Path

I completed my undergraduate studies at the [University of Macau](https://www.um.edu.mo/), majoring in Computer Science. It was during my undergraduate final year project that I first had the chance to encounter deep learning content. I made minor modifications based on [CycleGAN](https://arxiv.org/pdf/1703.10593), but in reality, I did not achieve meaningful results; this experience was more of a superficial exploration.

During my master’s program of Visual Computing at [Universität des Saarlandes](https://www.uni-saarland.de/), I was introduced to Physical-based rendering(PBR), with ray tracing serving as a representative technique.  This field ignited a profound interest in me. Unlike my earlier tentative attempts, I fully committed to it. I built a complete ray tracing renderer from scratch, a project that has continuously guided my exploration of PBR algorithms. For my master's thesis, I focused on extending the research on [Regression-based Monte Carlo Integration](https://arxiv.org/pdf/2211.07422), under the supervision of [Qinqin Hua](https://qingqin-hua.com/) and [Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html). Looking back, exploring this thesis project was a bittersweet experience. On one hand, the paper itself was academically comprehensive and held a certain degree of intellectual interest. On the other hand, that was where its value largely ended. In my view, the final work was essentially a highly polished piece of paper in the traditional sense: refined in details but lacking breakthrough innovation.

Currently, I return to the [University of Macau](https://www.um.edu.mo/) to pursue my PhD, supervised by [Prof.Xiaodong Cun](https://vinthony.github.io/academic/) and [Prof. Chi-Man Pun](https://cmpun.github.io/). My research now focuses on 3D Vision (3DV) and its applications in the field of AIGC. Through my ongoing studies, I am more convinced than ever that data-driven methods still hold immense untapped potential, both in terms of breadth and depth. On a subconscious level, I still hope to revisit PBR in the future—this time, exploring it through the lens of deep learning, with the goal of reimagining traditional PBR workflows using data-driven approaches.

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

As time has passed, I've gradually formed coarse yet meaningful principles regarding research and learning, which now guide my approach:

1. Consistency
When it comes to learning, the goals we pursue are often lifelong. In most research, consistency stands as the most critical factor. Firstly, in terms of rarity, maintaining long-term consistency is arguably as challenging as the emergence of natural talent. Secondly, consistency is a skill that can be cultivated. As growth and learning follow an inherently non-linear curve, only through continuous learning and accumulation can we achieve genuine progress. Furthermore, consistency is also the most sustainable and efficient way to avoid internal friction and waste. It helps you coordinate and leverage your energy over the long run, rather than relying on fleeting bursts of motivation that quickly fade."

Moments of "genius-driven inspiration" are thrilling, akin to surging waves that crest to great heights. Yet the ultimate purpose of a wave lies not in its peak, but in the journey it undertakes. True progress, too, is forged step by step: small, daily efforts accumulate to yield something meaningful—a principle embodied by every great scholar.

2. Time Management
Time management is far more than simply creating a schedule or timetable; it requires a holistic understanding and coordinated planning of a project, from the granular detail of daily tasks to the overarching project timeline. The foundation of good time management lies in your comprehensive grasp of your task. Only when you have a comprehensive grasp of your tasks can you design a schedule that is truly appropriate. This foresight prevents unwelcome interruptions from misaligned tasks or engaging in random, meaningless activities to "fill time." Consequently, you can fully commit your energy to critical tasks, ensuring your focus remains squarely on your objectives. This not only makes goal achievement more efficient but also far more fulfilling.

3. Idea > Achievement
From an idealistic perspective, research transcends mere engineering; it is an act of exploration that, in turn, guides the practice of engineering. Yet the landscape has shifted in recent years. As data-driven trends grow increasingly prominent, engineering itself has emerged as a valuable form of contribution. As researchers, I believe that while we acknowledge the value of engineering, we must also cultivate and deliver something far more unique—something only we can bring to the table. Such differentiation hinges on prioritizing the ideas behind the work, for engineering, at its core, is just the realization of those ideas.
I believe the core of impactful work lies in its original intent. Whether it’s unearthing a practical application for an algorithm or proposing an innovative task, a compelling idea offers both guiding direction and exploratory potential. It should feel natural and convincing. While popular tasks inevitably attract many to implement them, it is the distinctiveness and depth of the idea itself that truly elevates a contribution.

4. Learning by Doing
“Idea > Achievement” does not mean valuing ideas over practice in the process of research。On the contrary, hands-on practice and the evolution of ideas function in a synergistic cycle. Only through practice can reasonable ideas be derived, and only good ideas can guide better practices.In research, ideas serve to solve or analyze problems, and these problems are, in turn, discovered and evaluated through practice. Detaching ideas from real-world work renders them as empty fantasies devoid of practical value.

5. Designing Experiments
Much like time management, experiment design is a reflection of your comprehensive project understanding. A well-designed experiment is characterized by its simplicity, efficiency, and its ability to demonstrate feasibility while facilitating problem analysis. Overly complex or cumbersome experiments unnecessarily hinder progress, leading to wasted time, diminished motivation, and even difficulty in achieving desired outcomes. Conversely, effective experiments are decomposable; breaking them down into small, feedback-driven steps enables real-time adjustments, fostering an efficient, positive cycle of ‘test-learn-improve.’

6. Knowing When to “Think Hard”
In practice, ‘critical thinking’ should be applied strategically. Unnecessary overthinking breeds internal friction, diminishes efficiency, and causes a misalignment between goals and actions, ultimately harming research.
My advice: Concentrate your deep thinking on experiment design and result analysis. Avoid overcomplicating the experiment itself. If an experiment necessitates continuous ‘hard thinking’ to execute, it likely indicates a flawed or unclear design, excessive convolution, or a lack of essential preparation.