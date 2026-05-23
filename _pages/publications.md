---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<!-- {% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

I currently manage the scalable oversight team at [Anthropic](https://www.anthropic.com/), where we work on providing reliable training rewards for Claude without human supervision. I'm also the research lead for the [Anthropic Fellows Program](https://alignment.anthropic.com/2025/anthropic-fellows-program-2026/), a 4-6 month fellowship for alignment research. I've personally supervised 15+ fellows, and my fellows have published in a wide range of areas, including AI control, CoT monitoring and faithfulness, scalable oversight, automated alignment research, and interpretability. If you're interested in working with me, apply to the Fellows Program [here](https://job-boards.greenhouse.io/anthropic/jobs/5023394008)!

Previously I've worked on building model organisms of misalignment, understanding chain-of-thought monitoring and implementing control evaluations as part of Anthropic's Alignment Science team. Before that, I was a PhD student in the [Department of Statistics](https://www.stats.ox.ac.uk/) at the University of Oxford, where I was supervised by [Arnaud Doucet](https://www.stats.ox.ac.uk/~doucet/) and [George Deligiannidis](https://www.stats.ox.ac.uk/~deligian/) and worked on the theory of diffusion models. I've also spent time with the [UK Frontier AI Taskforce](https://www.gov.uk/government/publications/frontier-ai-taskforce-second-progress-report) (now the UK AI Safety Institute) and remain excited about helping governments to understand and respond to the development of potentially broadly superhuman AI systems.

## Publications

[SLEIGHT-Bench: A Benchmark of Evasion Attacks Against Agent Monitors](https://arxiv.org/abs/2605.16626). Elle Najt, Colin Toft, Tyler Tracy, Fabien Roger, **Joe Benton**. *arXiv preprint arXiv:2605.16626*, 2026.

[Efficiently Aligning Language Models with Online Natural Language Feedback](https://arxiv.org/abs/2605.04356). Christine Ye, **Joe Benton**. *arXiv preprint arXiv:2605.04356*, 2026.

[Removing Sandbagging in LLMs by Training with Weak Supervision](https://arxiv.org/abs/2604.22082). Emil Ryd, Henning Bartsch, Julian Stastny, **Joe Benton**, Vivek Hebbar. *International Conference on Machine Learning*, 2026.

[Evaluating Control Protocols for Untrusted AI Agents](https://arxiv.org/abs/2511.02997). Jon Kutasov, Chloe Loughridge, Yuqi Sun, Henry Sleight, Buck Shlegeris, Tyler Tracy, **Joe Benton**. *AAAI 2026 Workshop on Trust and Control in Agentic AI*, 2026.

[Optimizing AI Agent Attacks With Synthetic Data](https://arxiv.org/abs/2511.02823). Chloe Loughridge, Paul Colognese, Avery Griffin, Tyler Tracy, Jon Kutasov, **Joe Benton**. *AAAI 2026 Workshop on Trust and Control in Agentic AI*, 2026.

[Natural Emergent Misalignment from Reward Hacking in Production RL](https://arxiv.org/abs/2511.18397). Monte MacDiarmid, Benjamin Wright, Jonathan Uesato, **Joe Benton**, Jon Kutasov, Sara Price et al. *arXiv preprint arXiv:2511.18397*, 2025.

[Chain of Thought Monitorability: A New and Fragile Opportunity for AI Safety](https://arxiv.org/abs/2507.11473). Tomek Korbak, Mikita Balesni, Elizabeth Barnes, Yoshua Bengio, **Joe Benton**, Joseph Bloom, Mark Chen, Alan Cooney, Allan Dafoe, Anca Dragan, Scott Emmons, Owain Evans, David Farhi, Dan Hendrycks, et al. *arXiv preprint arXiv:2507.11473*, 2025.

[SHADE-Arena: Evaluating Sabotage and Monitoring in LLM Agents](https://arxiv.org/abs/2506.15740). Jonathan Kutasov, Yuqi Sun, Paul Colognese, Teun van der Weij, Linda Petrini, Chen Bo Calvin Zhang, John Hughes, Xiang Deng, Henry Sleight, Tyler Tracy, Buck Shlegeris, **Joe Benton**. *arXiv preprint arXiv:2506.15740*, 2025.

[Reasoning Models Don't Always Say What They Think](https://arxiv.org/abs/2505.05410). Yanda Chen, **Joe Benton**, Ansh Radhakrishnan, Jonathan Uesato, Carson Denison, John Schulman, Arushi Somani, Peter Hase, Misha Wagner, Fabien Roger, Vlad Mikulik, Samuel R. Bowman, Jan Leike, Jared Kaplan, Ethan Perez. *arXiv preprint arXiv:2505.05410*, 2025.

[Constitutional Classifiers: Defending against Universal Jailbreaks across Thousands of Hours of Red Teaming](https://www.anthropic.com/research/constitutional-classifiers). Mrinank Sharma, Meg Tong, Jesse Mu, Jerry Wei, Jorrit Kruthoff, Scott Goodfriend, Euan Ong, Alwin Peng, Raj Agarwal, Cem Anil, Amanda Askell, Nathan Bailey, **Joe Benton**, Emma Bluemke, et al. _arXiv preprint arXiv:2501.18837_, 2025.

[Teaching Models to Verbalize Reward Hacking in Chain-of-Thought Reasoning](https://arxiv.org/abs/2506.22777). Miles Turpin, Andy Arditi, Meihua Li, **Joe Benton**, Julian Michael. *ICML 2025 Workshop on Reliable and Responsible Foundation Models*, 2025.

[Inverse Scaling in Test-Time Compute](https://arxiv.org/abs/2507.14417). Aryo Pradipta Gema, Alexander Hägele, Runjin Chen, Andy Arditi, Jacob Goldman-Wetzler, Kit Fraser-Taliente, Henry Sleight, Linda Petrini, Julian Michael, Beatrice Alex, Pasquale Minervini, Yanda Chen, **Joe Benton**, Ethan Perez. *Transactions on Machine Learning Research*, 2025.

[Many-shot Jailbreaking](https://www.anthropic.com/research/many-shot-jailbreaking). Cem Anil, Esin Durmus, Nina Panickssery, Mrinank Sharma, **Joe Benton**, Sandipan Kundu, Joshua Batson, Meg Tong, Jesse Mu, Daniel Ford et al. _Advances in Neural Information Processing Systems_, 2024.

[Sabotage Evaluations for Frontier Models](https://arxiv.org/abs/2410.21514). **Joe Benton**, Misha Wagner, Eric Christiansen, Cem Anil, Ethan Perez, Jai Srivastav, Esin Durmus, Deep Ganguli, Shauna Kravec, Buck Shlegeris et al. _arXiv preprint arXiv:2410.21514_, 2024.

[From Denoising Diffusions to Denoising Markov Models](https://academic.oup.com/jrsssb/advance-article/doi/10.1093/jrsssb/qkae005/7564909). **Joe Benton**, Yuyang Shi, Valentin De Bortoli, George Deligiannidis, Arnaud Doucet. _Journal of the Royal Statistical Society Series B: Statistical Methodology_, 86(2):286−301, 2024.

[When Do Universal Image Jailbreaks Transfer Between Vision-Language Models?](https://arxiv.org/abs/2407.15211). Rylan Schaeffer, Dan Valentine, Luke Bailey, James Chua, Cristóbal Eyzaguirre, Zane Durante, **Joe Benton**, Brando Miranda, Henry Sleight, John Hughes et al. _NeurIPS 2024 Workshop on Responsibly Building the Next Generation of Multimodal Foundational Models_, 2024.

[Nearly d-Linear Convergence Bounds for Diffusion Models via Stochastic Localization](https://arxiv.org/abs/2308.03686). **Joe Benton**, Valentin De Bortoli, Arnaud Doucet, George Deligiannidis. _International Conference on Learning Representations_, 2024.

[Error Bounds for Flow Matching Methods](https://arxiv.org/abs/2305.16860). **Joe Benton**, George Deligiannidis, Arnaud Doucet. _Transactions on Machine Learning Research_, February 2024.

[Alpha-divergence Variational Inference Meets Importance Weighted Auto-Encoders: Methodology and Asymptotics](https://www.jmlr.org/papers/volume24/22-1160/22-1160.pdf). Kamélia Daudel, **Joe Benton**, Yuyang Shi, Arnaud Doucet. _Journal of Machine Learning Research_, 24(243):1−83, 2023.

[Measuring Feature Sparsity in Language Models](https://arxiv.org/abs/2310.07837). Mingyang Deng, Lucas Tao, **Joe Benton**. _NeurIPS 2023 Workshop on Socially Responsible Language Modelling Research_, 2023.

[A Continuous Time Framework for Discrete Denoising Models](https://papers.nips.cc/paper_files/paper/2022/hash/b5b528767aa35f5b1a60fe0aaeca0563-Abstract-Conference.html). Andrew Campbell, **Joe Benton**, Valentin De Bortoli, Tom Rainforth, George Deligiannidis, Arnaud Doucet. _Advances in Neural Information Processing Systems_, 2022.

[Polysemanticity and Capacity in Neural Networks](https://arxiv.org/abs/2210.01892). Adam Scherlis, Kshitij Sachan, Adam S. Jermyn, **Joe Benton**, Buck Shlegeris. _arXiv preprint, arXiv:2210.01892_, 2022.

## Research Blog Posts

[A3: An Automated Alignment Agent for Safety Finetuning](https://alignment.anthropic.com/2026/automated-alignment-agent/). Jifan Zhang, Henry Sleight, **Joe Benton**. *Anthropic Alignment Science Blog*, 2026.

[Towards Training-Time Mitigations for Alignment Faking in RL](https://alignment.anthropic.com/2025/alignment-faking-mitigations/). Johannes Gasteiger, Vlad Mikulik, Hoagy Cunningham, Misha Wagner, Benjamin Wright, Jonathan Uesato, **Joe Benton**, Monte MacDiarmid, Fabien Roger, Evan Hubinger. *Anthropic Alignment Science Blog*, 2025.

[Training Fails to Elicit Subtle Reasoning in Current Language Models](https://alignment.anthropic.com/2025/subtle-reasoning/). Misha Wagner, Fabien Roger, Hoagy Cunningham, Johannes Gasteiger, **Joe Benton**, Vlad Mikulik. *Anthropic Alignment Science Blog*, 2025.

<!-- ## Talks

Some talks will go here -->
