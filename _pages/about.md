---
layout: about
title: about
permalink: /
subtitle: AI Researcher &amp; Engineer &mdash; Foundation Models &amp; Machine Learning &middot; Healthcare AI &middot; Power Systems

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true
  more_info: >
    <p>Ph.D., Computer Science &amp; Engineering, 2025</p>
    <p>University of Nevada, Reno</p>
    <p>Reno, Nevada, USA</p>

selected_papers: true
social: true

announcements:
  enabled: true
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
---

I am an AI researcher and machine learning engineer (Ph.D., Computer Science and Engineering, University of Nevada, Reno) working on **foundation models, distributed and federated learning, and mathematical optimization**. My core focus is **healthcare AI**: privacy-preserving, wearable-based methods for detecting early-stage cognitive decline, and LLMs for clinical decision support. I also bring this same machine learning toolkit to **power systems**, applying federated learning to grid event detection, EV ecosystems, and infrastructure monitoring.

Before moving into AI, I spent nearly a decade as a control and power systems engineer, including data center design and operations. That background lets me build models that work on real sensors, real constraints, and real operations.

<div class="card mb-4" style="background-color: var(--global-card-bg-color, #161b22); border: 1px solid var(--global-divider-color, #30363d); border-left: 4px solid #3fb950; border-radius: 8px; padding: 1.25rem; margin: 1.5rem 0;">
  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap; gap: 1rem;">
    <div style="flex: 1; min-width: 260px;">
      <span style="display: inline-block; background: rgba(63, 185, 80, 0.15); color: #3fb950; font-size: 0.75rem; font-weight: 700; padding: 0.2rem 0.6rem; border-radius: 4px; text-transform: uppercase; margin-bottom: 0.45rem;">🆕 #1 Featured Newly Published Spotlight &bull; MDPI Sustainability (2026, 18(20), 10574)</span>
      <h4 style="margin-bottom: 0.35rem; font-weight: 700; font-size: 1.08rem;">
        1. <a href="https://www.mdpi.com/2071-1050/18/20/10574" target="_blank" rel="noopener" style="text-decoration: none;">Sustainable Smart Grid Resilience and Renewable Integration Using Multi-Agent Reinforcement Learning</a> <span style="font-size: 0.82rem; color: #3fb950;">(MDPI Sustainability, 2026, 18(20), 10574 &bull; DOI: 10.3390/su182010574)</span>
      </h4>
      <p style="margin-bottom: 0.55rem; color: var(--global-text-color-light, #8b949e); font-size: 0.9rem;">
        Decentralized MARL feeder reconfiguration, Q-learning restoration, coordinated battery dispatch, and autonomous Volt&ndash;VAr droop control achieving <strong>+51% PV hosting capacity</strong>, <strong>55.1% isolated load restoration across 496 double-fault pairs</strong>, and <strong>72.7% fewer feasibility evaluations</strong> across IEEE 33-bus and 179-bus Oberrhein networks.
      </p>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap; margin-bottom: 0.85rem;">
        <a href="https://www.mdpi.com/2071-1050/18/20/10574" target="_blank" rel="noopener" class="btn btn-sm btn-success" style="font-size: 0.82rem; font-weight: 700;">📄 Read Open-Access on MDPI</a>
        <a href="https://www.mdpi.com/2071-1050/18/20/10574/pdf" target="_blank" rel="noopener" class="btn btn-sm btn-primary" style="font-size: 0.82rem; font-weight: 700;">📥 Download Official MDPI PDF</a>
        <a href="https://doi.org/10.3390/su182010574" target="_blank" rel="noopener" class="btn btn-sm btn-outline-success" style="font-size: 0.8rem; font-weight: 600;">🔗 DOI: 10.3390/su182010574</a>
        <a href="/papers/sustainable-smart-grid-resilience-marl.html" class="btn btn-sm btn-outline-info" style="font-size: 0.8rem; font-weight: 600;">⚡ Interactive MARL Simulator &amp; BibTeX</a>
      </div>
      <h4 style="margin-bottom: 0.35rem; font-weight: 700; font-size: 1.05rem;">
        2. <a href="/papers/solar-subspace-latent-adapter-peft.html" style="text-decoration: none;">SOLAR: Communication-Efficient Model Adaptation via Subspace-Oriented Latent Adapter Reparametrization</a>
      </h4>
      <p style="margin-bottom: 0.75rem; color: var(--global-text-color-light, #8b949e); font-size: 0.9rem;">
        Achieves <strong>35.1% lower adapter memory &amp; gradient sync payload</strong> and <strong>1.54x faster distributed synchronization</strong> than LoRA across LLaMA-3, RoBERTa, GPT-2, and Vision Transformers (+0.3% average GLUE score).
      </p>
      <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
        <a href="/papers/solar-subspace-latent-adapter-peft.html" class="btn btn-sm btn-outline-primary" style="font-size: 0.8rem; font-weight: 600;">🧮 SOLAR Page &amp; Calculator</a>
        <a href="https://www.researchgate.net/profile/Mahmoud-Sajjadi-2" target="_blank" rel="noopener" class="btn btn-sm btn-outline-info" style="font-size: 0.8rem;">🔬 ResearchGate</a>
        <a href="https://github.com/mahmoudsajjadi/solar-peft" target="_blank" rel="noopener" class="btn btn-sm btn-outline-secondary" style="font-size: 0.8rem;">💻 PyTorch Code</a>
        <a href="/research-hub.html" class="btn btn-sm btn-outline-secondary" style="font-size: 0.8rem;">📚 All 21 Publications Hub</a>
      </div>
    </div>
  </div>
</div>

## Selected results

- **+51% renewable PV hosting capacity &amp; 72.7% fewer feasibility evaluations** during multi-fault smart grid restoration using decentralized MARL ([**Read Open-Access on MDPI** (*Sustainability*, 2026, 18(20), 10574)](https://www.mdpi.com/2071-1050/18/20/10574) | [**Official MDPI PDF**](https://www.mdpi.com/2071-1050/18/20/10574/pdf) | [Interactive Simulator &amp; BibTeX](/papers/sustainable-smart-grid-resilience-marl.html)).
- **80% less training time** for federated and split learning on heterogeneous clients ([*IEEE Internet of Things Journal*, 2025](/papers/speed-up-federated-learning-dynamic-tiering.html)).
- **35% lower communication and storage** than LoRA for fine-tuning ViT, LLaMA, and GPT-2 with subspace reparameterization ([**SOLAR**, interactive page &amp; BibTeX](/papers/solar-subspace-latent-adapter-peft.html)).
- **26% less slower-side compute** in decentralized learning with convergence analysis ([*IEEE ICDCS*, 2024](/papers/decentralized-multi-agent-learning-icdcs.html)).
- **88&ndash;90% accuracy** on 3,877 power grid events across 23 PMUs with a privacy-preserving federated framework using homomorphic encryption ([*IEEE PESGM*](/papers/pmu-data-federated-learning-event-classification.html)).
- **22% lower energy consumption** in infrastructure projects drawing on my prior data center engineering experience.

## Areas of expertise

**Foundation Models &amp; Machine Learning.** Federated and split learning, parameter-efficient fine-tuning (LoRA and subspace reparameterization) for LLaMA, GPT-2, and ViT, and mathematical optimization for distributed training.

**Healthcare AI.** Multimodal wearable data (PPG, EDA, EEG, IMU) to extract physiological biomarkers and distinguish Mild Cognitive Impairment from healthy cohorts; cloud pipelines on AWS SageMaker; clinical decision-support with LLMs.

**Power Systems.** Privacy-preserving federated fault detection and PMU event classification across the grid, and EV smart charging and V2G.

## Open-source curations

- [**Awesome AI Coding Tools (2026 Taxonomy & Benchmarks)**](https://github.com/mahmoudsajjadi/awesome-ai-coding-tools) &mdash; Curated 3-tier catalog of autonomous software engineering agents, local open-weight models, MCP servers, SWE-bench benchmarks, and an [Interactive GPU VRAM Calculator](https://mahmoudsajjadi.github.io/awesome-ai-coding-tools/).
- [**Awesome AI Research Tools (2026)**](https://github.com/mahmoudsajjadi/awesome-ai-research-tools) &mdash; Curated directory of scientific literature discovery engines, citation synthesis graphs, LaTeX equation workflows, and an [Academic Research Stack Navigator](https://mahmoudsajjadi.github.io/awesome-ai-research-tools/).

I am open to research scientist, ML engineer, and applied AI roles. The best way to reach me is by email.
