---
layout: default
---
## About Me

<img class="profile-picture" src="personal picture.jpg">

Hi! My name is Ahmed Attia and I'm on an endeavor to satisfy my curiosity and contribute to the betterment of humanity through research in Artificial Intelligent systems. I recieved my MSc from [Mohamed bin Zayed University of Artificial Intelligence: MBZUAI](https://mbzuai.ac.ae/) under the supervision of [Prof. Alham Fikri Aji](https://scholar.google.com/citations?user=0Cyfqv4AAAAJ&hl=en/). My research focuses on Reinforcement Learning, Continual Learning and AI for Science.

<figure class="mission-viz" aria-labelledby="mission-caption">
  <div class="mission-console">
    <div class="mission-status" aria-hidden="true">
      <span><i></i> AGENT ONLINE</span>
      <span>ACTION <b id="mission-action">EXPLORE</b></span>
      <span id="mission-step">STEP 000</span>
    </div>
    <svg viewBox="0 0 700 282" role="img" aria-labelledby="mission-title mission-desc">
      <title id="mission-title">A reinforcement-learning agent pursuing human flourishing</title>
      <desc id="mission-desc">An agent continually observes the world, takes actions, receives feedback from many human outcomes, and updates its policy toward long-term human flourishing.</desc>
      <defs>
        <filter id="mission-glow" x="-100%" y="-100%" width="300%" height="300%"><feGaussianBlur stdDeviation="4" result="blur"/><feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
      </defs>

      <g class="world-grid">
        <path d="M28 57H672M28 107H672M28 157H672M28 207H672M28 257H672M78 32V282M178 32V282M278 32V282M378 32V282M478 32V282M578 32V282" />
      </g>

      <g class="world-signals">
        <circle cx="75" cy="77" r="4"/><circle cx="130" cy="238" r="4"/><circle cx="213" cy="63" r="4"/>
        <circle cx="287" cy="252" r="4"/><circle cx="378" cy="69" r="4"/><circle cx="463" cy="239" r="4"/>
        <circle cx="555" cy="62" r="4"/><circle cx="624" cy="245" r="4"/>
      </g>

      <g class="trajectory">
        <path class="trail trail-ghost" d="M58 222C105 192 116 97 174 118S230 226 292 199S347 80 407 111S463 217 519 178S570 84 636 91" />
        <path class="trail trail-live" d="M58 222C105 192 116 97 174 118S230 226 292 199S347 80 407 111S463 217 519 178S570 84 636 91" />
        <g class="state-nodes">
          <circle cx="58" cy="222" r="7"/><circle cx="174" cy="118" r="7"/><circle cx="292" cy="199" r="7"/>
          <circle cx="407" cy="111" r="7"/><circle cx="519" cy="178" r="7"/>
        </g>
        <g class="agent-token" filter="url(#mission-glow)">
          <circle r="13"/><path d="M-5 0h10M0-5v10"/>
          <animateMotion dur="7s" repeatCount="indefinite" path="M58 222C105 192 116 97 174 118S230 226 292 199S347 80 407 111S463 217 519 178S570 84 636 91" />
        </g>
      </g>

      <g class="mission-goal" transform="translate(636 91)">
        <circle class="goal-orbit" r="31"/><circle class="goal-pulse" r="22"/><circle class="goal-core" r="9"/>
      </g>
      <text class="goal-kicker" x="636" y="39" text-anchor="middle">SUPREME MISSION</text>
      <text class="goal-label" x="636" y="54" text-anchor="middle">human flourishing ↑</text>
    </svg>
    <div class="mission-readout" aria-hidden="true">
      <span>EST. LONG-TERM UTILITY <b id="mission-utility">+0.42</b></span>
      <span>OBSERVE · ACT · LEARN · REPEAT</span>
    </div>
  </div>
  <figcaption id="mission-caption">A policy in perpetual motion—learning from the world, acting under uncertainty, and steering toward better futures.</figcaption>
</figure>

<script>
  (() => {
    const root = document.querySelector('.mission-viz');
    if (!root || window.matchMedia('(prefers-reduced-motion: reduce)').matches) return;
    const actions = ['explore', 'reason', 'cooperate', 'discover', 'build', 'reflect'];
    const action = root.querySelector('#mission-action');
    const utility = root.querySelector('#mission-utility');
    const step = root.querySelector('#mission-step');
    let tick = 0;
    window.setInterval(() => {
      tick += 1;
      action.textContent = actions[tick % actions.length].toUpperCase();
      utility.textContent = `+${(0.42 + (tick % 9) * 0.03).toFixed(2)}`;
      step.textContent = `STEP ${String(tick).padStart(3, '0')}`;
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
