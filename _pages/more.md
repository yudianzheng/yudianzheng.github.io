---
permalink: /more/
title: "More"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

{% include toc %}

## My Academic Path

> I completed my undergraduate studies at the [University of Macau](https://www.um.edu.mo/), majoring in Computer Science. It was during my undergraduate final year project that I first had the chance to encounter deep learning content. I made minor modifications based on [CycleGAN](https://arxiv.org/pdf/1703.10593), but in reality, I did not achieve meaningful results; this experience was more of a superficial exploration.
> 
> During my master’s program of Visual Computing at [Universität des Saarlandes](https://www.uni-saarland.de/), I was introduced to Physical-based rendering(PBR), with ray tracing serving as a representative technique.  This field ignited a profound interest in me. Unlike my earlier tentative attempts, I fully committed to it. I built a complete ray tracing renderer from scratch, a project that has continuously guided my exploration of PBR algorithms. For my master's thesis, I focused on extending the research on [Regression-based Monte Carlo Integration](https://arxiv.org/pdf/2211.07422), under the supervision of [Qinqin Hua](https://qingqin-hua.com/) and [Pascal Grittmann](https://graphics.cg.uni-saarland.de/people/grittmann.html). Looking back, exploring this thesis project was a bittersweet experience. On one hand, the paper itself was academically comprehensive and held a certain degree of intellectual interest. On the other hand, that was where its value largely ended. In my view, the final work was essentially a highly polished piece of paper in the traditional sense: refined in details but lacking breakthrough innovation.
> 
> Currently, I return to the [University of Macau](https://www.um.edu.mo/) to pursue my PhD, supervised by [Prof.Xiaodong Cun](https://vinthony.github.io/academic/) and [Prof. Chi-Man Pun](https://cmpun.github.io/). My research now focuses on 3D Vision (3DV) and its applications in the field of AIGC. Through my ongoing studies, I am more convinced than ever that data-driven methods still hold immense untapped potential, both in terms of breadth and depth. On a subconscious level, I still hope to revisit PBR in the future—this time, exploring it through the lens of deep learning, with the goal of reimagining traditional PBR workflows using data-driven approaches.

## Research Interests

> As I outlined in My Academic Path, I have experience with both PBR and AIGC in the field of CV. While these two domains qualify as “rendering” in a broad sense, their core logics differ fundamentally. PBR is grounded in theoretical rigor, relying on strict physical principles to model and describe the world objectively. Consequently, its results are unbiased, robust, and highly compressed, as algorithms distill complex phenomena into precise, interpretable rules. In contrast, AIGC is data-driven; it learns from vast amounts of real-world data to generate descriptions and recreations of the world. This enables the generation of complex scenes that would be extremely difficult to capture through theoretical modeling alone. However, this strength comes with trade-offs: data-driven outputs are often biased, suboptimal, redundant and unexplainable. Between model-driven and data-driven, there are many fundamental issues worth exploring.
> 
> I am interested in visual representation methods. Spanning techniques that range from NeRF (Neural Radiance Fields) to 3DGS (3D Gaussian Splatting) to PBR (Physically Based Rendering), as well as spaces that progress from latent space to vector space to pixel space, different visual representations exhibit distinct characteristics in terms of interpretability and editability. My interests include how these representation methods endow results with varying characteristics, the relationship between representation methods and their inherent characteristics, the processes for converting between representation methods, and the strategies for leveraging diverse representation methods.
> 
> The second area of my interest is extending PBR using large models. Traditional PBR faces significant limitations and has somewhat stagnated, due to some key reasons:
> (1) Modeling the real world is extremely challenging. Real-world scenes are highly complex, influenced by numerous factors, making accurate replication difficult;
> (2) Algorithm implementation is cumbersome. Even building a basic renderer requires addressing multiple aspects—including camera systems, geometry processing, material simulation, light sources, and rendering algorithms. Among these, a single advanced rendering algorithm like Bidirectional Path Tracing (BDPT) involves even more complex considerations, which are highly unfavorable for code implementation, use, and maintenance;
> (3) Different rendering methods impose strict constraints on scenes themselves. Most are designed for specific scenarios and cannot guarantee a general improvement in rendering speed;
> (4) Additionally, many of these algorithms are still optimized for CPUs, failing to fully leverage the parallel processing capabilities of modern hardware.
This domain represents a 'blue ocean' of untapped potential. Since the precise methods for integrating large models into PBR pipelines, and the optimal ways to represent this combination, are still being defined, numerous promising avenues for future research and development remain open.
> 
> My research is focused on 3D Vision (3DV), a field currently undergoing rapid development. The development of new backbone models has demonstrated the effectiveness of scaling laws in 3D domains, a concept previously successful in 2D. This is a significant advancement, bringing 3D Vision much closer to capturing the inherent properties of real-world. This evolution also signals a growing alignment between CV and CG. Consequently, advancements in 3DV offer substantial benefits for AIGC, providing crucial support for tasks such as video generation, 3D asset creation, and scene understanding. Crucially, we are still in the early stages of exploring the full potential of the synergy.

## Evolving Research Perspectives

> As time has passed, I've gradually formed coarse yet meaningful principles regarding research and learning, which now guide my approach:
> 
> 1. Consistency:
> When it comes to learning, the goals we pursue are often lifelong. In most research, consistency stands as the most critical factor. Firstly, in terms of rarity, maintaining long-term consistency is arguably as challenging as the emergence of natural talent. Secondly, consistency is a skill that can be cultivated. As growth and learning follow an inherently non-linear curve, only through continuous learning and accumulation can we achieve genuine progress. Furthermore, consistency is also the most sustainable and efficient way to avoid internal friction and waste. It helps you coordinate and leverage your energy over the long run, rather than relying on fleeting bursts of motivation that quickly fade. 
> Moments of "genius-driven inspiration" are thrilling, akin to surging waves that crest to great heights. Yet the ultimate purpose of a wave lies not in its peak, but in the journey it undertakes. True progress, too, is forged step by step: small, daily efforts accumulate to yield something meaningful—a principle embodied by every great scholar.
> 
> 2. Time Management:
> Time management is far more than simply creating a schedule or timetable; it requires a holistic understanding and coordinated planning of a project, from the granular detail of daily tasks to the overarching project timeline. The foundation of good time management lies in your comprehensive grasp of your task. Only when you have a comprehensive grasp of your tasks can you design a schedule that is truly appropriate. This foresight prevents unwelcome interruptions from misaligned tasks or engaging in random, meaningless activities to "fill time." Consequently, you can fully commit your energy to critical tasks, ensuring your focus remains squarely on your objectives. This not only makes goal achievement more efficient but also far more fulfilling.
> 
> 3. Idea > Achievement:
> From an idealistic perspective, research transcends mere engineering; it is an act of exploration that, in turn, guides the practice of engineering. Yet the landscape has shifted in recent years. As data-driven trends grow increasingly prominent, engineering itself has emerged as a valuable form of contribution. As researchers, I believe that while we acknowledge the value of engineering, we must also cultivate and deliver something far more unique—something only we can bring to the table. Such differentiation hinges on prioritizing the ideas behind the work, for engineering, at its core, is just the realization of those ideas.
> I believe the core of impactful work lies in its original intent. Whether it’s unearthing a practical application for an algorithm or proposing an innovative task, a compelling idea offers both guiding direction and exploratory potential. It should feel natural and convincing. While popular tasks inevitably attract many to implement them, it is the distinctiveness and depth of the idea itself that truly elevates a contribution.
> 
> 4. Learning by Doing:
> “Idea > Achievement” does not mean valuing ideas over practice in the process of research。On the contrary, hands-on practice and the evolution of ideas function in a synergistic cycle. Only through practice can reasonable ideas be derived, and only good ideas can guide better practices.In research, ideas serve to solve or analyze problems, and these problems are, in turn, discovered and evaluated through practice. Detaching ideas from real-world work renders them as empty fantasies devoid of practical value.
> 
> 5. Designing Experiments:
> Much like time management, experiment design is a reflection of your comprehensive project understanding. A well-designed experiment is characterized by its simplicity, efficiency, and its ability to demonstrate feasibility while facilitating problem analysis. Overly complex or cumbersome experiments unnecessarily hinder progress, leading to wasted time, diminished motivation, and even difficulty in achieving desired outcomes. Conversely, effective experiments are decomposable; breaking them down into small, feedback-driven steps enables real-time adjustments, fostering an efficient, positive cycle of ‘test-learn-improve.’
> 
> 6. Knowing When to “Think Hard”:
> In practice, ‘critical thinking’ should be applied strategically. Unnecessary overthinking breeds internal friction, diminishes efficiency, and causes a misalignment between goals and actions, ultimately harming research.
My advice: Concentrate your deep thinking on experiment design and result analysis. Avoid overcomplicating the experiment itself. If an experiment necessitates continuous ‘hard thinking’ to execute, it likely indicates a flawed or unclear design, excessive convolution, or a lack of essential preparation.