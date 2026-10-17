---
layout: page
permalink: /research/
title: research
description: Research and engineering across foundation models, healthcare AI, and power systems.
nav: true
nav_order: 1
---

<div class="card mb-4" style="background-color: var(--global-card-bg-color, #161b22); border: 1px solid var(--global-divider-color, #30363d); border-radius: 8px; padding: 1.25rem; margin-bottom: 2rem;">
  <div style="display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 1rem;">
    <div>
      <h4 style="margin-bottom: 0.25rem; font-weight: 700;">🔬 Interactive Research &amp; Citation Hub</h4>
      <p style="margin-bottom: 0; color: var(--global-text-color-light, #8b949e); font-size: 0.95rem;">
        Explore all 21 publications, preprints, ResearchGate full-texts, benchmarks, and 1-click BibTeX/IEEE/APA citations across Foundation Models, Healthcare AI, and Power Systems.
      </p>
    </div>
    <div style="display: flex; gap: 0.5rem; flex-wrap: wrap;">
      <a href="/papers/solar-subspace-latent-adapter-peft.html" class="btn btn-sm btn-outline-primary" style="white-space: nowrap; font-weight: 600; padding: 0.5rem 1rem; border-radius: 6px;">🧮 SOLAR Spotlight &amp; Calculator</a>
      <a href="/papers/sustainable-smart-grid-resilience-marl.html" class="btn btn-sm btn-outline-success" style="white-space: nowrap; font-weight: 600; padding: 0.5rem 1rem; border-radius: 6px;">⚡ Smart Grid MARL Simulator</a>
      <a href="/research-hub.html" class="btn btn-sm btn-primary" style="white-space: nowrap; font-weight: 600; padding: 0.5rem 1.2rem; border-radius: 6px;">Open Research Hub &rarr;</a>
    </div>
  </div>
</div>

## AI for healthcare

Early detection of cognitive decline (Alzheimer's disease, Mild Cognitive Impairment) from wearable and multimodal signals, at Connected Future Labs.

- Automated pipelines that ingest, clean, and harmonize streaming PPG, EDA, accelerometer, skin temperature, Muse EEG, and IMU data.
- Physiological biomarkers (HRV, sympathetic/parasympathetic responses, neural features) that separate MCI from healthy cohorts.
- AWS S3 and SageMaker pipelines that audit data quality and detect signal anomalies for downstream classification.
- Clinical decision-support with large language models; chapters on AI in diagnosis, treatment, and rheumatoid arthritis.

## Foundation models and distributed machine learning

Federated learning, split learning, and decentralized multi-agent learning for heterogeneous edge devices, with convergence analysis in convex and non-convex settings.

- **SOLAR** ([Interactive Paper Page &amp; Calculator](/papers/solar-subspace-latent-adapter-peft.html) | [arXiv:2604.08368](https://arxiv.org/abs/2604.08368) | [PyTorch Code](https://github.com/mahmoudsajjadi/solar-peft)): Subspace-oriented latent adapter reparameterization achieving **35.1% lower communication and storage than LoRA** and **1.54x faster distributed sync** on ViT, LLaMA, RoBERTa, and GPT-2.
- Dynamic tiering for federated learning ([DTFL](/papers/speed-up-federated-learning-dynamic-tiering.html)): **80% shorter training time** on heterogeneous clients (*IEEE Internet of Things Journal*, 2025; Impact Factor: 9.0).
- Communication-efficient workload balancing for decentralized learning ([ComDML](/papers/decentralized-multi-agent-learning-icdcs.html)): **26% less slower-side compute** (*IEEE ICDCS*, 2024; 21.9% acceptance rate).
- Privacy-preserving SplitFed with distance correlation and patch shuffling.

## AI for power systems

Federated, multi-agent, and privacy-preserving machine learning for the grid and EV ecosystems, informed by nearly a decade of prior control and power/data center engineering experience.

- **Sustainable Smart Grid Resilience &amp; MARL** ([Interactive Paper Page &amp; Simulator](/papers/sustainable-smart-grid-resilience-marl.html) | [DOI: 10.3390/su182010574](https://doi.org/10.3390/su182010574) | *MDPI Sustainability*, Vol. 18, No. 20, 10574, 2026): Decentralized multi-agent reinforcement learning for feeder reconfiguration, fault restoration, and battery dispatch, achieving **+51% PV hosting capacity**, **55.1% isolated load restoration across 496 double-fault pairs**, and **72.7% fewer feasibility evaluations**.
- Federated XGBoost and MLP classifiers for current, voltage, and frequency faults: **91% accuracy** using 80% of local data.
- Privacy-preserving federated event classification with additive homomorphic encryption ([PESGM](/papers/pmu-data-federated-learning-event-classification.html)): **3,877 events, 23 PMUs, 88&ndash;90% accuracy** on highly non-IID data.
- Feature collusion attacks on PMU data-driven event classifiers ([IEEE ISGT](/papers/feature-collusion-attack-pmu-classification.html)).
- Generative AI and distributed ML for EV ecosystems (smart charging, V2G): **+44.5% battery SOH estimation accuracy** and **100% CAN bus anomaly detection** in the surveyed frameworks.
- Data center infrastructure engineering (2014&ndash;2022): redesigned power/cooling for a **22% reduction in energy consumption** and led three builds worth **$35M**.
