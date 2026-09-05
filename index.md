---
layout: default
---
## About Me

<img class="profile-picture" src="personal picture.jpg">

Hi! My name is Ahmed Attia and I'm on an endeavor to satisfy my curiosity and contribute to the betterment of humanity through research in Artificial Intelligent systems. I recieved my MSc from [Mohamed bin Zayed University of Artificial Intelligence: MBZUAI](https://mbzuai.ac.ae/) under the supervision of [Prof. Alham Fikri Aji](https://scholar.google.com/citations?user=0Cyfqv4AAAAJ&hl=en/). My research focuses on Reinforcement Learning, Continual Learning and AI for Science.

<figure class="mission-viz">
  <div class="mission-console" role="img" aria-label="An active reinforcement-learning agent takes an action, receives a reward, and pursues the goal of maximizing humanity's long-term utility.">
    <div class="mission-agent">
      <div class="mission-metric">
        <span>ACTION</span>
        <strong id="mission-action">explore</strong>
      </div>
      <div class="mission-metric">
        <span>REWARD</span>
        <strong id="mission-reward">+0.42</strong>
      </div>
    </div>
    <div class="mission-objective">
      <span>SUPREME MISSION</span>
      <strong>maximize humanity's long-term utility</strong>
    </div>
  </div>
</figure>

<script>
  (() => {
    const root = document.querySelector('.mission-viz');
    if (!root || window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
    const transitions = [
      ['explore', '+0.42'],
      ['reason', '+0.18'],
      ['cooperate', '+0.71'],
      ['build', '+0.54'],
      ['fail', '-0.23'],
      ['reflect', '+0.09'],
      ['learn', '+0.63']
    ];
    const action = root.querySelector('#mission-action');
    const reward = root.querySelector('#mission-reward');
    let tick = 0;
    window.setInterval(() => {
      tick += 1;
      const transition = transitions[tick % transitions.length];
      action.textContent = transition[0];
      reward.textContent = transition[1];
      reward.classList.toggle('is-negative', transition[1][0] === '-');
    }, 1167);
  })();
</script>

## Research Interest

I am interested in Reinforcement Learning, Continual Learning and AI for Science.

## Timeline

<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">Feb 2026 - May 2026</span>
    <strong>Student Resident, Institute of Foundation Models</strong>
    <span>MBZUAI · Reinforcement-learning post-training for mathematical reasoning and code generation.</span>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">May 2025 - Jul 2025</span>
    <strong>R&amp;D Machine Learning Engineer</strong>
    <span>Yalla Group · Deep reinforcement learning and distributed training for a Draw Dominoes agent.</span>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">Aug 2024 - 2026</span>
    <strong>MSc in Natural Language Processing</strong>
    <span>Mohamed bin Zayed University of Artificial Intelligence.</span>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">Jul 2022 - Jun 2024</span>
    <strong>Natural Language Processing Engineer Intern</strong>
    <span>SpeedLegal · Retrieval-augmented generation and information extraction for contract review.</span>
  </div>
  <div class="timeline-item">
    <span class="timeline-date">Aug 2020 - Jul 2024</span>
    <strong>BSc in Artificial Intelligence</strong>
    <span>Kafr El-Sheikh University, Faculty of Artificial Intelligence.</span>
  </div>
</div>

## Research

1. **[Improving Low-Resource Machine Translation via Round-Trip Reinforcement Learning](https://arxiv.org/abs/2601.12535)**  
   **Ahmed Attia** and Alham Fikri Aji. arXiv preprint arXiv:2601.12535, 2026.

2. **[Accurate and Diverse LLM Mathematical Reasoning via Automated PRM-Guided GFlowNets](https://arxiv.org/abs/2504.19981)**  
   Adam Younsi, **Ahmed Attia**, Abdalgader Abubaker, Mohamed El Amine Seddik, Hakim Hacid, and Salem Lahlou. arXiv preprint arXiv:2504.19981, 2025.

[View all publications on Google Scholar](https://scholar.google.com/citations?user=8SPGWvEAAAAJ&hl=en).

---

> Hardwork Beats Talent, Eventually.
