---
layout: default
---
## About Me

<div class="profile-card">
  <img class="profile-picture" src="personal picture.jpg" alt="Ahmed Attia">
  <div class="profile-links" aria-label="Contact and social links">
    <a href="mailto:ahmed.attia@alumni.mbzuai.ac.ae" aria-label="Email Ahmed" title="Email">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M3 5h18v14H3zM3 6l9 7 9-7"/></svg>
    </a>
    <a href="https://github.com/Copticoder" aria-label="Ahmed on GitHub" title="GitHub">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2a10 10 0 0 0-3.16 19.49c.5.09.68-.22.68-.48v-1.69c-2.78.6-3.37-1.18-3.37-1.18-.45-1.16-1.11-1.47-1.11-1.47-.91-.62.07-.61.07-.61 1 .07 1.53 1.03 1.53 1.03.9 1.53 2.35 1.09 2.92.83.09-.65.35-1.09.64-1.34-2.22-.25-4.55-1.11-4.55-4.94 0-1.09.39-1.98 1.03-2.68-.1-.25-.45-1.27.1-2.64 0 0 .84-.27 2.75 1.02A9.58 9.58 0 0 1 12 6.7a9.6 9.6 0 0 1 2.5.34c1.91-1.29 2.75-1.02 2.75-1.02.55 1.37.2 2.39.1 2.64.64.7 1.03 1.59 1.03 2.68 0 3.84-2.34 4.68-4.57 4.93.36.31.68.92.68 1.86v2.88c0 .27.18.58.69.48A10 10 0 0 0 12 2z"/></svg>
    </a>
    <a href="https://www.linkedin.com/in/ahmed-emad-417174178/" aria-label="Ahmed on LinkedIn" title="LinkedIn">
      <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M5.3 3.5A2.3 2.3 0 1 1 5.3 8a2.3 2.3 0 0 1 0-4.5zM3.3 9.5h4v11h-4zM10 9.5h3.8V11c.8-1.2 2-2 3.8-2 4 0 4.7 2.6 4.7 6v5.5h-4v-4.9c0-1.2 0-2.8-1.8-2.8s-2.1 1.3-2.1 2.7v5h-4z"/></svg>
    </a>
  </div>
</div>

Hi! My name is Ahmed Attia and I'm on an endeavor to satisfy my curiosity and contribute to the betterment of humanity through research in Artificial Intelligent systems. I recieved my MSc from [Mohamed bin Zayed University of Artificial Intelligence: MBZUAI](https://mbzuai.ac.ae/) under the supervision of [Prof. Alham Fikri Aji](https://scholar.google.com/citations?user=0Cyfqv4AAAAJ&hl=en/) and [Prof. Salem Lahlou](https://lahlou.org/research-group/). I'm interested in Reinforcement Learning, Safe, Robust and Reliable ML Systems and AI for Science.

<figure class="mission-viz">
  <div class="mission-console" role="img" aria-label="An active reinforcement-learning agent takes an action, receives a reward, and pursues the goal of maximizing humanity's long-term utility.">
    <div class="mission-step">
      <span>STEP</span>
      <strong id="mission-step">000</strong>
    </div>
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
    const step = root.querySelector('#mission-step');
    let tick = 0;
    window.setInterval(() => {
      tick += 1;
      const transition = transitions[tick % transitions.length];
      action.textContent = transition[0];
      reward.textContent = transition[1];
      reward.classList.toggle('is-negative', transition[1][0] === '-');
      step.textContent = String(tick).padStart(3, '0');
    }, 1167);
  })();
</script>

## Publications

1. **[Improving Low-Resource Machine Translation via Round-Trip Reinforcement Learning](https://arxiv.org/abs/2601.12535)**  
   **Ahmed Attia** and Alham Fikri Aji. arXiv preprint arXiv:2601.12535, 2026.

2. **[Accurate and Diverse LLM Mathematical Reasoning via Automated PRM-Guided GFlowNets](https://arxiv.org/abs/2504.19981)**  
   Adam Younsi, **Ahmed Attia**, Abdalgader Abubaker, Mohamed El Amine Seddik, Hakim Hacid, and Salem Lahlou. arXiv preprint arXiv:2504.19981, 2025.

[View all publications on Google Scholar](https://scholar.google.com/citations?user=8SPGWvEAAAAJ&hl=en).

## Blog

### [Exploring Ordered Sampling in Generative Flow Networks]({% post_url 2025-12-03-ordered-sampling-gflownets %})

*December 3, 2025*

Can choosing which trajectory lengths a GFlowNet sees first improve exploration? We study two simple curricula and find that learning from short trajectories before long ones is especially effective when rewards are sparse.

---

> Hardwork Beats Talent, Eventually.
