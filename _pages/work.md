---
layout: founder
permalink: /work/
title: "Selected work"
excerpt: "Systems and studies built for how organizations coordinate — LLM pipelines, field experiments, and web-scale measurement."
---

<section class="fx__intro">
  <p class="fx__eyebrow">Selected work</p>
  <h1 class="fx__display">Things I've built, and what they were built to find out.</h1>
  <p class="fx__lead">Research systems, production features, and field deployments — mostly Python, mostly shipped rather than described.</p>
</section>

<section>
  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">A shared organizational model for human–agent coordination</h2>
      <span class="fx__entry-scale">prototype + field studies</span>
    </div>
    <p class="fx__entry-body">With my advisor Julien Clement, I architected a research instrument that fuses curated corpora with live behavioral signals — messaging, calendar, and project tools — through retrieval-augmented generation, so that a structured picture of an organization's tasks, skills, and decisions stays current instead of going stale the week it is compiled. The deployment is being built for field studies that test whether a shared model measurably improves human decisions, and characterize when embedded AI agents help coordination and when they harm it.</p>
    <p class="fx__entry-stack">Python · RAG · agentic LLM pipelines · randomized and stepped-wedge designs</p>
  </div>

  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">LLM coaching systems for scaling knowledge sharing</h2>
      <span class="fx__entry-scale">300+ participants, RCT</span>
    </div>
    <p class="fx__entry-body">Built LLM coaching chatbots end to end — dialogue architecture, retrieval grounding, prompt design — and deployed them to more than 300 participants in a randomized controlled experiment. The evaluation framework was built from scratch alongside them: automated LLM-as-judge scoring, human annotation calibration, and causal modelling of treatment effects.</p>
    <p class="fx__entry-stack">Python · R · React · multi-turn dialogue, RAG, LLM-as-judge evaluation, causal inference</p>
  </div>

  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">Equity in AI-mediated task allocation</h2>
      <span class="fx__entry-scale">240,000+ tasks</span>
    </div>
    <p class="fx__entry-body">A zero- and few-shot LLM classification system, written without framework wrappers, to label hundreds of thousands of real task assignments. The result is the sharpest version of the autonomy argument: when people self-assign work without a shared, global view of who is doing what, the work quietly resegregates by gender. The paper won the OMT Best Student Paper Award and a Best Paper designation at the Academy of Management.</p>
    <p class="fx__entry-stack">Python · SQL · zero-/few-shot LLM classification, NLP, regression</p>
  </div>

  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">Web-scale engagement and retention modelling</h2>
      <span class="fx__entry-scale">40M+ posts, 21M+ questions</span>
    </div>
    <p class="fx__entry-body">A large-scale processing pipeline — SQL extraction, Python ETL, embedding-based featurization, deduplication and quality filtering over noisy web-scale text — feeding a matched difference-in-differences survival analysis of what actually keeps contributors on a platform. Reciprocity recruits newcomers; status retains the experienced; the switchover is measurable.</p>
    <p class="fx__entry-stack">Python · SQL · NLP pipelines, deduplication and quality filtering, Cox survival models</p>
  </div>

  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">Skills modelling at scale</h2>
      <span class="fx__entry-scale">Google, 2026</span>
    </div>
    <p class="fx__entry-body">NLP and computational modelling of skills on structured and unstructured workforce data, and models of emerging skills and workforce transition in the age of AI.</p>
    <p class="fx__entry-stack">Language-model techniques applied to workforce data</p>
  </div>

  <div class="fx__entry">
    <div class="fx__entry-head">
      <h2 class="fx__entry-name">Production ML and LLM features</h2>
      <span class="fx__entry-scale">Game1 · SYNTINELS</span>
    </div>
    <p class="fx__entry-body">Predictive ML models developed, deployed, and productized for youth soccer at Game1. Before that, an LLM-powered feature shipped end to end in production at SYNTINELS — prompt architecture, retrieval context injection, evaluation scripting — driving a 20% adoption increase measured by A/B-style evaluation.</p>
    <p class="fx__entry-stack">Python · production deployment · A/B evaluation</p>
  </div>
</section>

<section>
  <h2 class="fx__title">Stack</h2>
  <ul class="fx__chips">
    <li>Python</li>
    <li>PyTorch</li>
    <li>Transformers &amp; fine-tuning</li>
    <li>RAG</li>
    <li>Agentic pipelines</li>
    <li>LLM evaluation</li>
    <li>Embeddings</li>
    <li>SQL</li>
    <li>Web-scale ETL</li>
    <li>Causal inference</li>
    <li>RCT &amp; stepped-wedge design</li>
    <li>Survival analysis</li>
    <li>R</li>
    <li>React</li>
  </ul>
  <a class="fx__next" href="{{ base_path }}/research/">The research behind it</a>
</section>
