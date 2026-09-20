---
layout: page
permalink: /research/
title: research
description: Research and engineering across foundation models, healthcare AI, and power systems.
nav: true
nav_order: 1
---

## AI for healthcare

Early detection of cognitive decline (Alzheimer's disease, Mild Cognitive Impairment) from wearable and multimodal signals, at Connected Future Labs.

- Automated pipelines that ingest, clean, and harmonize streaming PPG, EDA, accelerometer, skin temperature, Muse EEG, and IMU data.
- Physiological biomarkers (HRV, sympathetic/parasympathetic responses, neural features) that separate MCI from healthy cohorts.
- AWS S3 and SageMaker pipelines that audit data quality and detect signal anomalies for downstream classification.
- Clinical decision-support with large language models; chapters on AI in diagnosis, treatment, and rheumatoid arthritis.

## Foundation models and distributed machine learning

Federated learning, split learning, and decentralized multi-agent learning for heterogeneous edge devices, with convergence analysis in convex and non-convex settings.

- Dynamic tiering for federated learning: **80% shorter training time** on heterogeneous clients (*IEEE Internet of Things Journal*, 2024).
- Communication-efficient workload balancing for decentralized learning: **26% less slower-side compute** (*IEEE ICDCS*, 2024; 21.9% acceptance rate).
- Privacy-preserving SplitFed with distance correlation and patch shuffling.
- SOLAR, a subspace-based parameter-efficient fine-tuning method: **35% lower communication and storage than LoRA** on ViT, LLaMA, and GPT-2 (under review).

## AI for power systems

Federated and privacy-preserving machine learning for the grid and EV ecosystems, informed by nearly a decade of prior control and power/data center engineering experience.

- Federated XGBoost and MLP classifiers for current, voltage, and frequency faults: **91% accuracy** using 80% of local data.
- Privacy-preserving federated event classification with additive homomorphic encryption: **3,877 events, 23 PMUs, 88&ndash;90% accuracy** on highly non-IID data.
- Feature collusion attacks on PMU data-driven event classifiers.
- Generative AI and distributed ML for EV ecosystems (smart charging, V2G): **+44.5% battery SOH estimation accuracy** and **100% CAN bus anomaly detection** in the surveyed frameworks.
- Data center infrastructure engineering (2014&ndash;2022): redesigned power/cooling for a **22% reduction in energy consumption** and led three builds worth **$35M**.
