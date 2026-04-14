---
layout: page
title: CV
permalink: /cv/
---

<style>
.cv-download { font-family: 'IBM Plex Mono', monospace; font-size: 0.8rem; color: var(--text-muted); float: right; margin-top: 0.5rem; }
.cv-download a { color: var(--accent); }
.cv-subtitle { font-family: 'IBM Plex Mono', monospace; font-size: 0.85rem; color: var(--text-muted); margin-top: -0.5rem; margin-bottom: 1.5rem; }
.cv-contact { font-family: 'IBM Plex Mono', monospace; font-size: 0.78rem; color: var(--text-muted); margin-bottom: 2rem; }
.cv-contact a { color: var(--accent); }
.cv-section { margin-top: 2rem; }
.cv-section h2 { font-size: 1.1rem; text-transform: uppercase; letter-spacing: 0.08em; border-bottom: 1px solid var(--border); padding-bottom: 0.2rem; margin-bottom: 1rem; }
.cv-entry { display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0.1rem; }
.cv-entry-title { font-weight: 500; }
.cv-entry-loc { font-size: 0.9rem; color: var(--text-muted); text-align: right; }
.cv-entry-role { font-style: italic; color: var(--text-muted); font-size: 0.95rem; }
.cv-entry-date { font-family: 'IBM Plex Mono', monospace; font-size: 0.78rem; color: var(--text-muted); text-align: right; }
.cv-entry-meta { display: flex; justify-content: space-between; margin-bottom: 0.4rem; }
.cv-bullets { margin-top: 0.3rem; margin-bottom: 1.2rem; padding-left: 1.2rem; }
.cv-bullets li { margin-bottom: 0.2rem; font-size: 0.97rem; }
.cv-skills-table { width: 100%; border-collapse: collapse; margin-bottom: 0.5rem; }
.cv-skills-table td { padding: 0.2rem 0.5rem 0.2rem 0; font-size: 0.95rem; vertical-align: top; }
.cv-skills-table td:first-child { font-weight: 500; white-space: nowrap; padding-right: 1.5rem; width: 30%; }
.cv-pub { margin-bottom: 0.6rem; font-size: 0.97rem; }
.cv-awards td { padding: 0.15rem 0; font-size: 0.95rem; vertical-align: top; }
.cv-awards td:first-child { font-family: 'IBM Plex Mono', monospace; font-size: 0.78rem; color: var(--text-muted); padding-right: 1.5rem; white-space: nowrap; }
</style>

<div class="cv-download"><a href="/assets/Ajinkya_Mulay_CV_26.pdf">↓ Download PDF</a></div>

# Ajinkya Kiran Mulay

<div class="cv-subtitle">ML Research Scientist · AI Safety & Interpretability</div>

<div class="cv-contact">
<a href="mailto:ajinkyamulay123@gmail.com">ajinkyamulay123@gmail.com</a> &nbsp;|&nbsp;
<a href="https://linkedin.com/in/ajinkyamulay">linkedin.com/in/ajinkyamulay</a> &nbsp;|&nbsp;
<a href="https://github.com/thehimalayanleo">github/thehimalayanleo</a> &nbsp;|&nbsp;
<a href="https://scholar.google.com/citations?user=H7x5hYoAAAAJ">Google Scholar</a>
</div>

---

<div class="cv-section">
<h2>Research Interests</h2>
<p>Frontier AI Safety, Interpretability, and Evaluations: I focus on mechanistic understanding of neural networks and building rigorous evaluation frameworks to detect and control harmful behavior in high-capability systems. During my PhD, I developed theoretically grounded sparsification methods under differential privacy and federated learning constraints, achieving near-SOTA performance with only 8–10% of dense parameters. At Meta Integrity, I design and deploy LLM-driven safety systems at scale across Facebook, Instagram, and Threads.</p>
</div>

<div class="cv-section">
<h2>Experience</h2>

<div class="cv-entry"><span class="cv-entry-title">Meta Platforms, Inc</span><span class="cv-entry-loc">Menlo Park, CA</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Senior Research Scientist (AI Safety / Integrity Evals)</span><span class="cv-entry-date">Feb 2026 – Present</span></div>
<ul class="cv-bullets">
<li>Own safety evaluations for integrity LLMs, building automated red-teaming/robustness suites (prompt-injection variants, policy-bypass probes, adversarial scenarios) to prevent regressions pre-rollout.</li>
<li>Develop user-experience metrics and operationalize them via stratified evaluation and holdouts to understand user retention patterns.</li>
<li>Translate new attacker patterns into targeted RL evals and related mitigations, closing the loop from incident signal spikes to launch decisions.</li>
<li><strong>Stack:</strong> PyTorch, Evals, AI safety, LLM tooling, Red teaming.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Meta Platforms, Inc</span><span class="cv-entry-loc">Menlo Park, CA</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Research Scientist</span><span class="cv-entry-date">Feb 2024 – Feb 2026</span></div>
<ul class="cv-bullets">
<li>Designed and deployed LLM systems for large-scale spam/scam detection across Facebook, Instagram, and Threads, achieving <strong>4x TPR</strong> improvements with detection latency under <strong>4 hours</strong>.</li>
<li>Fine-tuned large (<strong>>70B</strong>) language models with retrieval-augmented safety workflows and production instrumentation to detect spam anomalies.</li>
<li>Built large-scale behavior monitoring with LLM-assisted labeling and DBSCAN-style clustering to surface coordinated/novel attacker behaviors; curated safety-critical datasets (<strong>>1M samples</strong>) for post-training and fine-tuning.</li>
<li><strong>Stack:</strong> PyTorch, PHP, Integrity, Spam.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">ECE, Purdue University</span><span class="cv-entry-loc">West Lafayette, IN</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Graduate Research Assistant</span><span class="cv-entry-date">Jun 2023 – Dec 2023</span></div>
<ul class="cv-bullets">
<li>Authored SPriFed-OMP, a differentially private federated learning algorithm for sparse basis recovery in high-dimensional regimes (p ≫ n). Achieved accurate recovery with n = O(√p) samples using only 8–10% of model parameters.</li>
<li>Combined OMP-style coordinate selection with differential privacy noise injection, isolating informative parameter subsets aligned with interpretable functional components.</li>
<li><strong>Stack:</strong> PyTorch, Differential Privacy, Federated Learning, Sparse Learning.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Meta (Facebook)</span><span class="cv-entry-loc">Menlo Park, CA</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">PhD Software Engineering Intern</span><span class="cv-entry-date">May 2022 – Aug 2022</span></div>
<ul class="cv-bullets">
<li>Designed and deployed a modular end-to-end production stack for Federated Semi-Supervised Learning (FSSL) vision tasks.</li>
<li>Replicated performance benchmarks with FixMatch and SimCLR on real devices.</li>
<li><strong>Stack:</strong> C++, TorchScript, Python, PyTorch.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Meta (Facebook)</span><span class="cv-entry-loc">Menlo Park, CA</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">PhD Software Engineering Intern</span><span class="cv-entry-date">May 2021 – Aug 2021</span></div>
<ul class="cv-bullets">
<li>Developed a fast, scalable private ML algorithm using PCA with differential privacy, outperforming SOTA by <strong>15%</strong> (test accuracy).</li>
<li>Improved performance-to-privacy trade-off by more than <strong>35%</strong> via varying tree restarts for DP-FTRL.</li>
<li><strong>Stack:</strong> Python, PyTorch, Differential Privacy, Federated Learning.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">SuperPower Research, Psychological Sciences, Purdue</span><span class="cv-entry-loc">West Lafayette, IN</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Graduate Research Assistant</span><span class="cv-entry-date">Aug 2020 – May 2023</span></div>
<ul class="cv-bullets">
<li>Designed a statistical-power modeling engine (NIH-funded) achieving &lt;5% error while reducing computation by <strong>90%</strong> vs. SOTA.</li>
<li>Proposed semi-supervised data augmentation and dimensionality reduction methods improving engine stability and power estimation variance.</li>
<li><strong>Stack:</strong> PyTorch, R, Bayesian Learning, Hypothesis Testing, Differential Privacy.</li>
</ul>
</div>

<div class="cv-section">
<h2>Other Research Experience</h2>

<div class="cv-entry"><span class="cv-entry-title">AI Safety Camp</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Community Member</span><span class="cv-entry-date">Jan 2026 – Present</span></div>
<ul class="cv-bullets">
<li>Collaborate with a cross-disciplinary group modeling frontier AI risk, focusing on how "AI slop" (high-volume, low-signal synthetic content) is created.</li>
<li>Design and run evaluation frameworks to detect and quantify AI slop across platforms and modalities.</li>
<li>Conduct interpretability analyses on how slop-like data distributions affect internal model representations (neuron/feature activations).</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">BlueDot Impact Technical AI Safety Course</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Participant</span><span class="cv-entry-date">2025</span></div>
<ul class="cv-bullets">
<li>Completed structured coursework on technical and governance dimensions of AI safety, covering alignment, interpretability, and catastrophic risk from frontier systems.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">OpenMined</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Community Member</span><span class="cv-entry-date">Mar 2020 – Mar 2023</span></div>
<ul class="cv-bullets">
<li>Explored the relationship between Differential Privacy and Adversarial Robustness; quantified DP/FL impact on real-world systems (FedPerf).</li>
<li><strong>Stack:</strong> PyTorch, PySyft, Git.</li>
</ul>
</div>

<div class="cv-section">
<h2>Education</h2>

<div class="cv-entry"><span class="cv-entry-title">Purdue University</span><span class="cv-entry-loc">West Lafayette, IN</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">PhD in Electrical and Computer Engineering</span><span class="cv-entry-date">Aug 2018 – Aug 2024</span></div>
<ul class="cv-bullets">
<li>Advised by Prof. Xiaojun Lin &nbsp;|&nbsp; GPA: 3.6/4.0</li>
<li>Thesis: Developed private and non-private sparse learning algorithms with provable convergence under extreme sample scarcity, achieving near-SOTA accuracy with ≤10% of dense parameters.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">IIT Hyderabad</span><span class="cv-entry-loc">Hyderabad, India</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">B.Tech (with Honors) in Electrical Engineering</span><span class="cv-entry-date">Aug 2014 – May 2018</span></div>
<ul class="cv-bullets">
<li>Advised by Prof. Bheemarjuna Reddy &nbsp;|&nbsp; GPA: 8.88/10</li>
<li>Research Focus: Inference-aware game-theoretic framework for unlicensed LTE and Wi-Fi bands.</li>
</ul>
</div>

<div class="cv-section">
<h2>Skills</h2>
<table class="cv-skills-table">
<tr><td>Frontier LLM Systems</td><td>Fine-tuning ≥70B models, RAG-based safety workflows, alignment evaluation.</td></tr>
<tr><td>Efficient ML</td><td>Sparse training, parameter reduction, structured optimization, extreme low-sample regimes (n ~ √p).</td></tr>
<tr><td>Safety & Integrity</td><td>Large-scale spam/scam detection, high-TPR safety filters, behavior anomaly detection.</td></tr>
<tr><td>Theory</td><td>Convergence proofs, DP-SGD, private PCA, sparse recovery, rational iteration for optimizer orthogonalization.</td></tr>
<tr><td>Kernel Engineering</td><td>Triton, block-sparse FlashAttention, CSR-format sparsity masks, H100 kernel optimization.</td></tr>
<tr><td>Technical</td><td>PyTorch, Triton, C++, Golang, TorchScript, PHP, distributed ML pipelines.</td></tr>
</table>
</div>

<div class="cv-section">
<h2>Projects</h2>

<div class="cv-entry"><span class="cv-entry-title">Halley-Gram-Muon: Cubic Convergence for Optimizer Orthogonalization</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Independent Research</span><span class="cv-entry-date">Jan 2026 – Present</span></div>
<ul class="cv-bullets">
<li>Replaced Newton-Schulz polynomial in GramMuon (used in Kimi K2, GLM-5) with a Halley rational iteration in Gram space achieving cubic convergence. Pareto-dominant over GramMuon T=5 on WikiText-103 and enwiki8: better model quality and 16–29% faster wall-clock.</li>
<li><strong>Stack:</strong> PyTorch, Triton, language model training.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Activation Sparsity as a Scheming Signal — Apart Research AI Control Hackathon</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Hackathon</span><span class="cv-entry-date">Mar 2026</span></div>
<ul class="cv-bullets">
<li>Mechanistic, output-independent scheming monitor: scheming agents produce more uniform MLP activations (lower Gini) across 15/18 layers. Threshold detector achieves AUROC = 0.745 with no output access (p = 0.0003, Cohen's d = 0.701), consistent across Qwen2.5 1.5B and 3B.</li>
<li><strong>Stack:</strong> PyTorch, Qwen2.5, mechanistic interpretability, activation probing.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Block-Sparse Causal Attention Kernel — Paradigm Attention Kernel Challenge</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Competition</span><span class="cv-entry-date">Apr 2026 – Present</span></div>
<ul class="cv-bullets">
<li>Triton kernel for block-sparse causal attention on H100 (CSR mask, head_dim=128). Applied OMP column-reuse intuition: KV-block reuse tiling across query row groups sharing support in sliding-window/banded patterns.</li>
<li><strong>Stack:</strong> Triton, PyTorch, H100, block-sparse FlashAttention.</li>
</ul>

<div class="cv-entry"><span class="cv-entry-title">Sparse Structured Agent for Financial Document QA — Sentient Arena OfficeQA</span><span class="cv-entry-loc">Remote</span></div>
<div class="cv-entry-meta"><span class="cv-entry-role">Competition</span><span class="cv-entry-date">Mar 2026 – Present</span></div>
<ul class="cv-bullets">
<li>Agentic reasoning system for multi-hop QA over Treasury Bulletin corpora, grounded in Sanskrit Kāraka grammar: query roles (agent, object, instrument) map to structured retrieval steps, with OMP-based decomposition identifying the minimal supporting document set.</li>
<li><strong>Stack:</strong> Goose, Python, OMP-style retrieval, agentic reasoning, Sanskrit Karaka grammar.</li>
</ul>
</div>

<div class="cv-section">
<h2>Journal Publications</h2>
<div class="cv-pub">Ajinkya Kiran Mulay, Xiaojun Lin. "SPriFed-OMP: A Differentially Private Federated Learning Algorithm for Sparse Basis Recovery." <em>Transactions of Machine Learning Research</em>, Purdue University.</div>
<div class="cv-pub">Ajinkya Kiran Mulay, Anand Basawade, Bheemarjuna Tamma, Anthony Franklin. "DFC: Dynamic UL-DL Frame Configuration for Improving Channel Access in eLAA." <em>IEEE Networking Letters</em>, IIT Hyderabad.</div>
</div>

<div class="cv-section">
<h2>Early Research Work</h2>
<div class="cv-pub">Ajinkya Kiran Mulay, Xiaojun Lin. "Humming-Bird: A Forward-Backward Based Differentially Private Federated Learning Algorithm for Sparse Basis Recovery." <em>In Review</em>, Purdue.</div>
<div class="cv-pub">Ajinkya Kiran Mulay, Xiaojun Lin. "Humming-Bird+: Batched and General Differentially Private FL Algorithms for Sparse Basis Recovery." <em>In Preparation</em>, Purdue.</div>
</div>

<div class="cv-section">
<h2>Workshop Presentations</h2>
<div class="cv-pub">Ajinkya Kiran Mulay, Sean Lane, Erin Hennes. "PowerGraph: Using neural networks and principal components to multivariate statistical power trade-offs." <em>AI for Science Workshop, ICML, July 2022</em> (Non-Archived). SuperPower Lab, Purdue.</div>
<div class="cv-pub">Ajinkya Kiran Mulay, Sean Lane, Erin Hennes. "Private Hypothesis Testing for Social Sciences." <em>Theory and Practice of Differential Privacy Workshop, ICML, July 2022</em> (Non-Archived). SuperPower Lab, Purdue.</div>
<div class="cv-pub">Rakshit Naidu, Harshita Diddee, Ajinkya Kiran Mulay, Aleti Vardhan, Krithika Ramesh, Ahmed Zamzam. "Towards Quantifying the Carbon Emissions of Differentially Private Machine Learning." <em>Socially Responsible ML Workshop, ICML, July 2021</em> (Non-Archived). OpenMined.</div>
<div class="cv-pub">Ajinkya Kiran Mulay, Tushar Semwal, Ayush Agrawal. "FedPerf: A Practitioners' Guide to Performance of Federated Learning Algorithms." <em>Pre-Registration Experiment Workshop, NeurIPS, December 2020</em> (Archived). OpenMined.</div>
</div>

<div class="cv-section">
<h2>Honors & Awards</h2>
<table class="cv-awards">
<tr><td>2026</td><td>Third Prize, Sentient Arena Cohort 0 OfficeQA Leaderboard.</td></tr>
<tr><td>2025</td><td>Winner, Grokipedia track, XAI Hackathon, CA, USA.</td></tr>
<tr><td>2023</td><td>Graduate Research Assistantship, ECE Department, Purdue.</td></tr>
<tr><td>2020</td><td>Graduate Research Assistantship, SuperPower Group, Purdue.</td></tr>
<tr><td>2018</td><td>Winner and World Finalist, Microsoft Imagine Cup Japan National Final (Emergensor Startup).</td></tr>
<tr><td>2018</td><td>Winner, Third Business Plan Competition, University of Tokyo.</td></tr>
<tr><td>2017</td><td>Two-Year Graduate Teaching Assistantship, ECE Department, Purdue.</td></tr>
<tr><td>2017</td><td>India-Japan Engineering Program Research Scholarship, University of Tokyo.</td></tr>
<tr><td>2016</td><td>Undergraduate Teaching Assistantship, IIT Hyderabad.</td></tr>
<tr><td>2016</td><td>Special Recognition and 8th Rank for Young Team, IEEE Signal Processing Cup.</td></tr>
<tr><td>2014</td><td>Academic Excellence Award, IIT Hyderabad.</td></tr>
<tr><td>2010</td><td>National Talent Search Examination (NTSE) Scholar, Govt. of India.</td></tr>
</table>
</div>

<div class="cv-section">
<h2>Invited Talks</h2>
<table class="cv-awards">
<tr><td>2023</td><td>Using neural networks and principal components to optimize multivariate statistical power trade-offs. <em>Modern Modeling Methods Conference</em> (Accepted; unable to attend).</td></tr>
<tr><td>2023</td><td>Privacy of Noisy SGD. <em>ML Theory, Cohere for AI</em>.</td></tr>
<tr><td>2022</td><td>How to promote open science under privacy. <em>Psychological Sciences Department, Purdue University</em>.</td></tr>
<tr><td>2022</td><td>PowerGraph: Using neural networks and principal components to multivariate statistical power trade-offs. <em>International Meeting of the Psychometric Society</em> (Accepted; unable to attend).</td></tr>
<tr><td>2021</td><td>Graphing multivariate statistical power manifolds with Machine Learning. <em>MCP Colloquium, Purdue University</em>.</td></tr>
<tr><td>2020</td><td>FedPerf: A Practitioners' Guide to Performance of Federated Learning Algorithms. <em>NeurIPS Pre-Registration Workshop</em>.</td></tr>
</table>
</div>

<div class="cv-section">
<h2>Teaching & Mentoring</h2>
<table class="cv-awards">
<tr><td>Jan–May 2022</td><td>Mentoring Undergraduate Students for the Anvil Co-Founder AI Matching Platform Development.</td></tr>
<tr><td>Aug 2019–May 2020</td><td>Graduate Teaching Assistant, ECE 27000 — <em>Introduction to Digital Design</em>, Purdue.</td></tr>
<tr><td>Aug 2018–May 2019</td><td>Graduate Teaching Assistant, ECE 20002 — <em>Electrical Engineering Fundamentals II</em>, Purdue.</td></tr>
</table>
</div>

<div class="cv-section">
<h2>Other Services</h2>
<table class="cv-awards">
<tr><td>2026</td><td>Attendee, EA Global, San Francisco, CA.</td></tr>
<tr><td>2024</td><td>Reviewer: NeurIPS, ICML TF2M Workshop, ICLR, DMLR, TMLR, ICLR Tiny Papers, Privacy Preserving AI Workshop at AAAI.</td></tr>
<tr><td>2023</td><td>Reviewer: NeurIPS, AAAI, ICML Tiny Papers, FAccT, ISIT, IJCAI, CHIL. Top Meta-Reviewer, AAAI Representation Learning Workshop.</td></tr>
<tr><td>2022</td><td>Reviewer: CHIL. Open Source: OpenMined, Gradio by HuggingFace. Professional Grant Reviewer, Purdue.</td></tr>
</table>
</div>
