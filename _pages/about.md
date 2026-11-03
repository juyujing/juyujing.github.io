---
permalink: /
title: "Yujing Ju"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<style>
body:has(.academic-home) { background: #f8faf9; }
body:has(.academic-home) #main { max-width: 1120px; margin: 0 auto; padding: 0 32px; animation: none; }
body:has(.academic-home) .page { width: 100%; float: none; padding: 0; margin: 0; }
body:has(.academic-home) .page__inner-wrap { float: none; width: 100%; }
body:has(.academic-home) .page__title { display: none; }
body:has(.academic-home) .page__content { float: none; width: 100%; }
.academic-home { color: #394b57; font-size: 16px; line-height: 1.8; }
.academic-home *, .academic-home *:before { box-sizing: border-box; }
.academic-home h1, .academic-home h2, .academic-home h3 { color: #223b46; padding: 0; border: 0; margin: 0; }
.academic-home h1, .academic-home h2 { font-family: Georgia, serif; font-weight: 400; letter-spacing: -.035em; }
.academic-home h1 { font-size: clamp(48px, 6vw, 76px); line-height: 1.1; margin: 14px 0 24px; }
.academic-home h2 { font-size: 32px; line-height: 1.25; }
.academic-home h3 { font-size: 20px; line-height: 1.4; font-weight: 600; }
.academic-home p { margin: 0 0 18px; }
.academic-home a { color: #286b70; text-decoration-thickness: 1px; }
.academic-home .kicker { font-size: 11px; text-transform: uppercase; letter-spacing: .17em; color: #5e7b7f; font-weight: 600; }
.ah-hero { display: grid; grid-template-columns: minmax(0, 1fr) 240px; gap: 80px; align-items: center; padding: 76px 0 64px; }
.ah-hero .ah-summary { font-size: 20px; line-height: 1.65; color: #455d69; max-width: 650px; }
.ah-photo { margin: 0; padding: 18px; border-radius: 30px; background: linear-gradient(145deg, #e8f1ed, #e8edf4); }
.ah-photo img { display: block; width: 100%; height: 260px; object-fit: cover; object-position: center 30%; border-radius: 20px; }
.ah-photo figcaption { font-size: 11px; color: #61767c; margin: 14px 0 0; text-align: center; letter-spacing: .05em; }
.ah-links { display: flex; align-items: center; flex-wrap: wrap; gap: 24px; margin-top: 28px; font-size: 13px; }
.ah-links a { text-decoration: none; }
.ah-links .ah-primary { background: #264f5c; color: white; padding: 10px 18px; border-radius: 10px; }
.ah-links .ah-primary:hover { background: #183c48; }
.ah-interests { display: grid; grid-template-columns: repeat(3, minmax(0, 1fr)); gap: 1px; background: #dfe8e6; border: 1px solid #dfe8e6; border-radius: 18px; overflow: hidden; margin-bottom: 68px; }
.ah-interest { background: #f0f5f3; padding: 25px 28px; }
.ah-interest strong { display: block; font-size: 14px; color: #294c54; margin-bottom: 7px; font-weight: 600; }
.ah-interest p { color: #667a81; font-size: 13px; line-height: 1.65; margin: 0; }
.ah-section { display: grid; grid-template-columns: 200px minmax(0, 1fr); gap: 48px; padding: 48px 0; border-top: 1px solid #dfe6e5; }
.ah-section header .kicker { margin-bottom: 12px; }
.ah-work { padding: 0 0 30px; margin: 0 0 30px; border-bottom: 1px solid #e4eae8; }
.ah-work:last-child { margin-bottom: 0; border-bottom: 0; padding-bottom: 0; }
.ah-meta { display: flex; flex-wrap: wrap; justify-content: space-between; gap: 8px; font-size: 12px; color: #75858c; margin-bottom: 10px; }
.ah-work h3 { margin-bottom: 12px; }
.ah-work p { font-size: 14px; }
.ah-work .ah-note { font-size: 12px; color: #72828b; }
.ah-projects { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
.ah-project { display: block; padding: 24px; border: 1px solid #dfe7e5; border-radius: 16px; background: white; text-decoration: none !important; transition: border-color .25s, box-shadow .25s; }
.ah-project:hover { border-color: #9abbb6; box-shadow: 0 8px 24px #23344709; }
.ah-project h3 { font-size: 16px; margin-bottom: 12px; }
.ah-project p { color: #657780; font-size: 13px; margin-bottom: 18px; }
.ah-project span { font-size: 12px; color: #286b70; }
.ah-background { display: grid; gap: 24px; }
.ah-background strong { font-size: 15px; color: #29434f; }
.ah-background p { font-size: 13px; color: #6b7d85; margin: 4px 0 0; }
.ah-contact { display: flex; justify-content: space-between; gap: 24px; align-items: center; background: linear-gradient(110deg, #eaf2ef, #eef2f8); border: 1px solid #e0e7e8; border-radius: 20px; padding: 32px; margin: 36px 0 64px; }
.ah-contact h2 { font-size: 25px; }
.ah-contact p { font-size: 13px; margin: 8px 0 0; color: #6b7f86; }
.ah-contact a { white-space: nowrap; font-size: 14px; }
@media (max-width: 760px) { body:has(.academic-home) #main { padding: 0 22px; } .ah-hero { grid-template-columns: 1fr 140px; gap: 28px; padding: 48px 0 36px; } .ah-photo { padding: 10px; border-radius: 22px; } .ah-photo img { height: 180px; border-radius: 14px; } .ah-photo figcaption { display: none; } .ah-hero .ah-summary { font-size: 17px; } .ah-interests { grid-template-columns: 1fr; margin-bottom: 38px; } .ah-interest { padding: 18px 22px; } .ah-section { grid-template-columns: 1fr; gap: 28px; padding: 34px 0; } .ah-section h2 { font-size: 28px; } .ah-projects { grid-template-columns: 1fr; } .ah-contact { display: block; padding: 24px; } .ah-contact a { display: inline-block; margin-top: 18px; } }
@media (max-width: 480px) { .ah-hero { grid-template-columns: 1fr; } .ah-photo { display: none; } .ah-links { gap: 18px; } }
@media (prefers-reduced-motion: reduce) { .ah-project { transition: none; } }
.ah-hero { grid-template-columns: minmax(0,1fr) 92px; gap: 36px; } .ah-photo { padding: 0; background: none; border-radius: 12px; opacity: .82; align-self: start; margin-top: 34px; } .ah-photo img { width: 92px; height: 112px; border-radius: 12px; filter: saturate(.65); border: 1px solid #e0e7e5; } .ah-photo figcaption { display: none; } @media(max-width:480px) { .ah-hero { grid-template-columns: 1fr; } }
</style>

<div class="academic-home">
<section class="ah-hero" aria-labelledby="intro-heading">
<div><p class="kicker">AI research · University of Florida</p><h1 id="intro-heading">Yujing Ju</h1><p class="ah-summary">Learning, reasoning, and reliable agents.</p><p>I am a Research Assistant at the <a href="https://www.ufl.edu/">University of Florida</a>, working with <a href="https://hobi.med.ufl.edu/profile/liu-mei/">Prof. Mei Liu</a> on large language models, reinforcement learning, and multi-agent systems.</p><p>My work connects model post-training with long-horizon reasoning, tool use, and rigorous evaluation.</p><div class="ah-links"><a class="ah-primary" href="/cv/">Curriculum vitae ↗</a><a href="https://github.com/juyujing">GitHub ↗</a><a href="https://www.linkedin.com/in/juyujing/">LinkedIn ↗</a><a href="mailto:yujingju@ufl.edu">Email ↗</a></div></div>
<figure class="ah-photo"><img src="/images/profile.png" alt="Portrait of Yujing Ju" width="204" height="260"><figcaption>YUJING JU · UNIVERSITY OF FLORIDA</figcaption></figure>
</section>
<div class="ah-interests" aria-label="Research interests"><div class="ah-interest"><strong>Model post-training</strong><p>Reinforcement learning and verifiable reasoning for language models.</p></div><div class="ah-interest"><strong>Long-horizon agents</strong><p>Multi-step planning, tool use, and agent trajectories.</p></div><div class="ah-interest"><strong>Reliable evaluation</strong><p>Privacy, domain reasoning, and repeatable model assessment.</p></div></div>
<section class="ah-section"><header><p class="kicker">01 / Research & engineering</p><h2>Selected work</h2></header><div>
<article class="ah-work"><div class="ah-meta"><span>Pharmaron · Algorithm Engineer Intern</span><time>Oct 2026–present</time></div><h3>Scaling laws for domain-specialized LLMs</h3><p>Run small-model experiments to extrapolate large-scale training performance and guide model size, training-token budgets, and compute allocation. Research targets competitive general-language benchmarks and expert-level pharmaceutical capabilities.</p><p>Investigate Engram-augmented MoE scaling laws across active expert parameters, conditional-memory capacity, and training data. Study constant-time n-gram lookup to expand knowledge capacity with limited added computation and preserve neural capacity for reasoning.</p><p class="ah-note">Compute–memory allocation · Megatron-LM · DeepSpeed · Triton · Training sharding</p></article>
<article class="ah-work"><div class="ah-meta"><span>University of Florida · Research Assistant</span><time>Aug 2025–present</time></div><h3>LLM privacy and evaluation</h3><p>Building privacy and ICD-coding benchmarks with 31,080 QA examples, 4,440 patient-level samples, and 1,860 valid ICD labels. Developing offline data generation and distributed training and evaluation workflows on the HiPerGator B200 cluster.</p><p class="ah-note">Privacy-preserving fine-tuning · Model evaluation · Distributed systems</p></article>
<article class="ah-work"><div class="ah-meta"><span>Hithink RoyalFlush · Algorithm Engineer Intern</span><time>Aug–Oct 2026</time></div><h3>AIME Investment Assistant</h3><p>Applied GRPO-based post-training to U.S. equity selection and investment recommendations for AInvest. Developed agent trajectories, long-horizon market analysis, quantitative strategies, and paper-trading simulations.</p><p>Adapted time-series reasoning, verifiable forecast actions, and explainable stock selection from VTA, StockR1, AlphaQuanter, SEP, and GRPO Financial Analyst.</p><p class="ah-note">GRPO · VeRL · DeepSpeed · Megatron-LM · Slime</p></article>
<article class="ah-work"><div class="ah-meta"><span>Heriot-Watt University · Graph learning</span><time>2024–2025</time></div><h3>Learning from asymmetric relationships</h3><p>Developed asymmetric graph convolution operators and investigated directed graph structures for recommendation, preserving citation direction and heterogeneous author–paper interactions.</p></article>
</div></section>
<section class="ah-section"><header><p class="kicker">02 / Open source</p><h2>Selected projects</h2></header><div class="ah-projects"><a class="ah-project" href="https://github.com/juyujing/Graduation-Project"><h3>Directed recommendation</h3><p>Directed and heterogeneous graph modeling for academic paper recommendation.</p><span>View repository ↗</span></a><a class="ah-project" href="https://github.com/juyujing/HyperGCN"><h3>Hypergraph recommendation</h3><p>Higher-order interactions for joint item and participant prediction.</p><span>View repository ↗</span></a><a class="ah-project" href="https://github.com/juyujing/GrOVe"><h3>Graph modeling library</h3><p>Open-source tools for graph-based mathematical modeling.</p><span>View repository ↗</span></a><a class="ah-project" href="https://github.com/juyujing/Capturer"><h3>Visually guided robotics</h3><p>A biomimetic hexapod integrating object recognition and motion planning.</p><span>View repository ↗</span></a></div></section>
<section class="ah-section"><header><p class="kicker">03 / Background</p><h2>Education & experience</h2></header><div class="ah-background"><div><strong>University of Florida</strong><p>PhD program in Biological and Medical Sciences · Master-en-route<br>Aug 2025–Jan 2027 (expected) · AI and large language models</p></div><div><strong>Heriot-Watt University</strong><p>BEng in Robotics · First Class Honours<br>Sep 2021–May 2025</p></div><div><strong>Pharmaron</strong><p>Algorithm Engineer Intern · Oct 2026–present</p></div></div></section>
<section class="ah-contact"><div><h2>Research & collaboration</h2><p>Language models, reinforcement learning, and agent systems.</p></div><a href="mailto:yujingju@ufl.edu">yujingju@ufl.edu ↗</a></section>
</div>
