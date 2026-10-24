<p align="center">
  <img src="https://raw.githubusercontent.com/FawadKarimi/FawadKarimi/main/assets/header.png" alt="Mohammad Fawad Karimi - Medical AI - 3D CT - Trustworthy ML" width="880"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/FawadKarimi/FawadKarimi/main/assets/now.png" alt="Current focus" width="880"/>
</p>

<p align="center">
  <a href="https://fawadkarimi.github.io/"><img src="https://img.shields.io/badge/Portfolio-fawadkarimi.github.io-0ea5e9?style=flat&logo=googlechrome&logoColor=white" height="22"/></a>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" height="22"/>
  <img src="https://img.shields.io/badge/3D_CT-0891b2?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/LIDC--IDRI-0e7490?style=flat" height="22"/>
  <img src="https://img.shields.io/badge/Uncertainty-164e63?style=flat" height="22"/>
  <a href="https://orcid.org/0009-0001-1598-4888"><img src="https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white" height="22"/></a>
</p>

---

Master's student in **Artificial Intelligence** at **Universitas Syiah Kuala** (Indonesian Government **KNB Scholar**). I work on **3D CT lung-nodule analysis** — the geometry of volumes, the disagreement between expert readers, and the evaluation habits that keep claims honest.

Most of my week is spent between a full CT volume and a claim I am willing to defend: sensitivity versus false positives, patient-disjoint splits, and what a model does when radiologists do not agree.

## What I work on

Volumetric detection pipelines, multi-rater supervision, disagreement-aware losses, and the boring reliability work that comes after a good ROC curve — **calibration**, **uncertainty**, **explanations**, and **failure cases**. A fair share of time goes to provenance: which seed, which cohort, which checkpoint actually produced the number.

## Geometry of the research

<p align="center">
  <img src="https://raw.githubusercontent.com/FawadKarimi/FawadKarimi/main/assets/volume-pipeline.png" alt="Volumetric CT research pipeline" width="880"/>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/FawadKarimi/FawadKarimi/main/assets/research-constellation.png" alt="Project constellation" width="880"/>
</p>

## Stack

Every day:

- **Python + PyTorch** — 2D/3D CNNs, Transformer tokens over deep feature maps, gated fusion
- **CT imaging craft** — HU windowing, resampling, patient-aware splits, LIDC-IDRI conventions
- **Evaluation discipline** — matched seeds, ablations, report every seed (not only the best)

Regularly:

- **Explainability** — Grad-CAM / attention maps as diagnostic tools, not marketing
- **Classical ML** — ensembles and feature selection when the dataset is tabular and the claim is clear
- **Linux GPU workflows** — reproducible training logs, checkpoint identity, host readiness checks
- **Technical writing** — manuscripts and portfolio notes that state limits as loudly as results

## Trustworthy ML, specifically

- Radiologist labels are **assessments**, not noiseless pathology truth
- **Patient-disjoint** evaluation is the floor; leakage is a research bug
- Calibration and uncertainty travel with every accuracy claim
- Explanations are evaluated — mixed or negative findings stay in the write-up
- Clinical validation is a separate claim; prototypes do not inherit it by proximity

## Selected projects

### [GLADS-CT](https://github.com/FawadKarimi/GLADS-CT)

Gated lung-nodule assessment with **disagreement-aware supervision**. ResNet-50 + Transformer attention + hierarchical gated fusion, compared under a shared protocol with patient-separated cohorts and matched seeds.

### [EXPLAINABLE 3D LIDC framework](https://github.com/FawadKarimi/EXPLAINABLE-3D-DEEP-LEARNING-FRAMEWORK-FOR-EARLY-LUNG-NODULE-DETECTION-USING-LIDC-IDRI-CT-SCANS)

Hybrid **3D CNN–Transformer** research code for early nodule detection on LIDC-IDRI, with Grad-CAM++ / integrated gradients style explainability hooks. An earlier public volume study, distinct from the ongoing private two-stage detector.

### [CLEAR3D-CT](https://github.com/FawadKarimi/CLEAR3D-CT-Candidate-Based-Lung-Nodule-Detection-with-Explainable-Attention-and-Residual-Learning)

Candidate-based detection with **explainable attention** and residual learning — the “find then refine” shape that mirrors clinical reading order.

### [Pancreatic CT prototype](https://github.com/FawadKarimi/Pancratic-Cancer-Detection)

A production-style **3D** PyTorch pipeline (preprocess → train → XAI metrics). Research prototype; clinical performance not established.

### [Breast cancer ensembles](https://github.com/FawadKarimi/Breast-Cancer-Diagnosis)

Optimized ensemble + feature selection on Wisconsin Diagnostic data — classical ML done carefully when deep learning is not the point.

### [Portfolio](https://fawadkarimi.github.io/)

The long-form map: private LIDC3D / ConsenDxFormer status, limits, and what is (and is not) claimed as of **October 2026**.

## How I work

- Prefer a weaker claim with a clean split over a stronger claim with leakage.
- Preserve disagreement in the labels; do not collapse experts into a false certainty.
- Ship the measured version: baselines, ablations, and the seeds that did not win.
- Documentation is part of the experiment — checkpoint hashes and cohort definitions belong in the repo.
- Educational medical prototypes stay labelled as educational.

## Currently

- Master's research on **volumetric** lung-nodule detection and **reader-aware** assessment (manuscript in preparation)
- Tightening evaluation narratives so uncertainty and explanation results sit beside accuracy
- Looking toward **funded PhD opportunities from 2027** in medical imaging and trustworthy machine learning

## Activity

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=FawadKarimi&show_icons=true&theme=radical&hide_border=true&bg_color=070b14&title_color=22d3ee&icon_color=67e8f9&text_color=e2e8f0&ring_color=0ea5e9" alt="GitHub stats"/>
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FawadKarimi&layout=compact&theme=radical&hide_border=true&bg_color=070b14&title_color=22d3ee&text_color=e2e8f0" alt="Top languages"/>
</p>
<p align="center">
  <img width="880" src="https://github-readme-activity-graph.vercel.app/graph?username=FawadKarimi&theme=react-dark&hide_border=true&bg_color=070b14&color=22d3ee&line=0ea5e9&point=67e8f9" alt="Contribution graph"/>
</p>

## Contact

- Portfolio: [fawadkarimi.github.io](https://fawadkarimi.github.io/)
- Academic: [mfkarimi@mhs.usk.ac.id](mailto:mfkarimi@mhs.usk.ac.id)
- Personal: [mohammadfawad2014@gmail.com](mailto:mohammadfawad2014@gmail.com)
- ORCID: [0009-0001-1598-4888](https://orcid.org/0009-0001-1598-4888)

Issues and discussions on any of the research repos above are welcome — especially if you work on multi-rater medical labels or volumetric evaluation.

---

Indonesia · medical imaging & trustworthy ML · [github.com/FawadKarimi](https://github.com/FawadKarimi)

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FawadKarimi&label=Profile%20views&color=0891b2&style=flat" alt="Profile views"/>
</p>
