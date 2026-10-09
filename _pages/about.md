---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I’m a Ph.D. student in the Department of [Computer Science](https://www.ucl.ac.uk/computer-science/ucl-computer-science) at University College London (UCL), advised by Professor [Jun Wang](http://www0.cs.ucl.ac.uk/staff/jun.wang/). After years in industry, I have returned to academia to pursue my passion for research. I previously received my M.Sc. in Computational Statistics and Machine Learning ([CSML](https://www.ucl.ac.uk/prospective-students/graduate/taught-degrees/computational-statistics-and-machine-learning-msc)) from UCL.

My research interests lie in Reinforcement Learning, Multi-Agent Systems, and Large Language Models. 

<style>
.research-pathway {
  margin: 2.25rem 0 2.5rem;
}

.research-pathway__intro {
  max-width: 46rem;
  margin-bottom: 1.75rem;
  color: #4b5563;
  font-size: 0.98em;
  line-height: 1.65;
}

.research-pathway__stages {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1.5rem;
  margin: 0;
  padding: 0;
  list-style: none;
}

.research-pathway__stage {
  position: relative;
  min-width: 0;
  padding-top: 0.85rem;
  border-top: 3px solid var(--stage-color);
}

.research-pathway__stage--reward {
  --stage-color: #13795b;
}

.research-pathway__stage--language {
  --stage-color: #2864a6;
}

.research-pathway__stage--discovery {
  --stage-color: #a23b4a;
}

.research-pathway__stage h3 {
  margin: 0.35rem 0 0.2rem;
  font-size: 1.05rem;
  line-height: 1.3;
}

.research-pathway__question {
  display: block;
  margin-bottom: 0.75rem;
  color: var(--stage-color);
  font-size: 0.78rem;
  font-weight: 700;
  letter-spacing: 0;
}

.research-pathway__stage p {
  margin: 0 0 0.85rem;
  color: #4b5563;
  font-size: 0.88rem;
  line-height: 1.55;
}

.research-pathway__papers {
  font-size: 0.82rem;
  line-height: 1.55;
}

.research-pathway__papers strong {
  display: block;
  margin-bottom: 0.2rem;
  color: #333;
  font-size: 0.75rem;
}

.research-pathway__papers a {
  text-decoration-thickness: 1px;
  text-underline-offset: 2px;
}

@media (max-width: 700px) {
  .research-pathway__stages {
    grid-template-columns: 1fr;
    gap: 1.75rem;
  }

  .research-pathway__stage {
    padding: 0 0 0.25rem 1rem;
    border-top: 0;
    border-left: 3px solid var(--stage-color);
  }

  .research-pathway__stage h3 {
    margin-top: 0;
  }
}
</style>

## Research Themes

<section class="research-pathway" aria-label="Research themes in value signals for agent learning">
  <p class="research-pathway__intro">How should an LLM-based agent decide what to learn from? My research explores three complementary notions of <strong>value</strong> for post-training agents, each suited to different forms of feedback and learning problems.</p>

  <ul class="research-pathway__stages">
    <li class="research-pathway__stage research-pathway__stage--reward">
      <h3>Verifiable Reward</h3>
      <span class="research-pathway__question">Did it work?</span>
      <p>When outcomes can be checked, scalar rewards provide a dependable training signal for reasoning, decision-making, and multi-agent coordination.</p>
      <div class="research-pathway__papers">
        <strong>Selected work</strong>
        <a href="https://arxiv.org/abs/2410.09671">OpenR</a> ·
        <a href="https://arxiv.org/abs/2410.07927">Efficient RL with LLM Priors</a> ·
        <a href="https://arxiv.org/abs/2503.09501">ReMA</a>
      </div>
    </li>

    <li class="research-pathway__stage research-pathway__stage--language">
      <h3>Language Value</h3>
      <span class="research-pathway__question">Why did it work?</span>
      <p>A scalar says how good an experience was; a language value function can also explain why, preserving structured knowledge that agents can reuse and refine.</p>
      <div class="research-pathway__papers">
        <strong>Selected work</strong>
        <a href="https://arxiv.org/abs/2411.14251">Natural Language RL</a> ·
        <a href="https://arxiv.org/abs/2607.28638">Stateful Predictive Knowledge</a>
      </div>
    </li>

    <li class="research-pathway__stage research-pathway__stage--discovery">
      <h3>Discovery Value</h3>
      <span class="research-pathway__question">What should we try next?</span>
      <p>For open-ended problems, discovery value can encode whichever signals matter for choosing what to generate, refine, or test next, such as performance, uncertainty, novelty, or information gain. In Large Discovery Models, a Gaussian-process acquisition function is one concrete instantiation.</p>
      <div class="research-pathway__papers">
        <strong>Selected work</strong>
        <a href="https://arxiv.org/abs/2608.15669">Large Discovery Models</a>
      </div>
    </li>
  </ul>
</section>

If you’d like to discuss potential collaborations or shared research interests, feel free to contact me at *yan.song.24[at]ucl.ac.uk*.

---

## News

- **[2026.10]** Recent paper updates: [**InfoPPO: Information-Time Proximal Policy Optimization**](https://arxiv.org/abs/2609.24380) and [**GanJiang: A self-learning scientific agent for X-ray diffraction**](https://arxiv.org/abs/2610.07862) are now available on arXiv! InfoPPO uses information density to guide credit propagation and policy updates for LLM reasoning, while GanJiang turns diffraction-analysis experience into reusable, validated skills. Our paper [*Hardware Co-Design Scaling Laws via Roofline Modelling for On-Device LLMs*](https://arxiv.org/abs/2602.10377) has also been accepted by **NeurIPS 2026**!

- **[2026.09]** Our paper [*ToolGate: Token-Efficient Pre-Call Control for Tool-Augmented Vision-Language Agents*](https://arxiv.org/abs/2606.03054) has been accepted by **EMNLP 2026**! [[Paper](https://arxiv.org/abs/2606.03054)]

- **[2026.08]** Our new paper [*Large Discovery Models: Empirically-grounded Model-Based Open-Ended Search*](https://arxiv.org/abs/2608.15669) is now available on arXiv! It targets the problem that language models don't know how to explore or exploit, an everlasting topic for RL scienctists.  [[Paper](https://arxiv.org/abs/2608.15669)]

- **[2026.07]** Our paper [*Learning Stateful Predictive Knowledge From Experience*](https://arxiv.org/abs/2607.28638) is available at the **ICML 2026 AIWILD Workshop**. [[Paper](https://arxiv.org/abs/2607.28638)] [[Blog](/posts/2026/08/learning-stateful-predictive-knowledge/)] [[X Post](https://x.com/YS01934823/status/2084367339647283308)]

- **[2026.05]** Here comes our second collaboration paper with [**Li Auto**](https://www.liauto.com/):  [*The Perceptual Bandwidth Bottleneck in Vision-Language Models: Active Visual Reasoning via Sequential Experimental Design*](https://arxiv.org/abs/2605.01345) and has been accepted by **ICML 2026** !

- **[2026.02]** We have been closely collaborating with [**Li Auto**](https://www.liauto.com/) on several research topics. Now we have released our first joint paper: [*Hardware Co-Design Scaling Laws via Roofline Modelling for On-Device LLMs*](https://arxiv.org/abs/2602.10377). Well Done Guys! Stay tuned for more to come out!

- **[2025.05]** Our paper [*Ask more, know better: Reinforce-Learned Prompt Questions for Decision Making with Large Language Models*](https://arxiv.org/abs/2310.18127) got accepted by **ECML-PKDD 2025**. A Testament to Persistence!

- **[2025.05]** We have successfully held the [**AAMAS 2025** Online AI Competitions](https://aamas2025.org/index.php/conference/program/competitions/)!

- **[2025.03]** **RL** can now interactively train two LLM agents to reason ! Our paper [*ReMA: Learning to Meta-think for LLMs with Multi-Agent Reinforcement Learning*](https://arxiv.org/abs/2503.09501) is available on Arxiv ! (**Neurips 2025**)

- **[2025.01]** Our paper [*Efficient Reinforcement Learning with Large Language Model Priors*](https://arxiv.org/pdf/2410.07927) got accepted by **ICLR 2025** !

- **[2024.10]** We release our LLM reasoning framework -- [***OpenR***](https://github.com/openreasoner/openr) !
