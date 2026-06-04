---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**[Download CV (PDF)](https://d-d-w404.github.io/Profile/files/wendeng-wang-cv.pdf)**

Education
======
* **M.S.** in Electrical and Computer Engineering, University of California, San Diego (UCSD), Sep 2024 – Jun 2026  
  GPA: 3.641/4.0
* **B.S.** in Computer Science, Central South University (CSU), Sep 2019 – Jun 2023  
  GPA: 88.69/100  
  Scholarships: National Scholarship (0.2%)

Research Experience
======
* **Development of an LLM-Agent for Cross-Platform Automated EEG Analysis** (Apr 2026 – Present)  
  SCCN Lab, UCSD  
  * Agent Skill Engineering: Developed standardized EEG analysis skills in an open Agent framework for LLM orchestration via Function Calling.  
  * Robustness and Guardrail Validation: Built evaluation frameworks and guardrails to minimize LLM hallucinations in EEG pipelines.

* **Real-Time EEG Stress Classification** (Mar 2025 – Oct 2025)  
  SCCN Lab, UCSD  
  * Explored correlations between stress states and independent EEG source components.  
  * Integrated Orica-Clean with predictive models for low-latency closed-loop stress forecasting.

* **Orica-Clean: Real-Time EEG Artifact Removal** (Jul 2025 – Jun 2026)  
  SCCN Lab, UCSD  
  * Replicated and validated ORICA in Python against MATLAB implementations.  
  * Built a production-ready package integrating ASR, ORICA, and ICLabel.  
  * Validated across multiple EEG datasets for robustness and generalization.

* **CNN-Based Framework for Automated Athlete Motion Classification** (Jun 2022 – Jun 2023)  
  Shootz, Central South University  
  * Developed annotation tools and a ResNet18 + YOLOv5 + ReID basketball video classification framework.  
  * Project evolved into the core technology of startup [Shootz](https://www.shootz.tech/).

Work Experience
======
* **Research Assistant** (Feb 2025 – Present)  
  SCCN Lab, UCSD  
  * Real-time EEG artifact removal with ORICA and ICLabel.  
  * Real-time stress and emotion detection; EEG data collection in movement and VR environments.

* **Machine Learning Engineer (Core Developer)** (Jun 2022 – Sep 2023)  
  Shootz, Central South University  
  * Led annotation tool and automation framework development for large-scale visual datasets.  
  * Dataset labeling, computer vision model training, and demo implementation.

* **Software Development Engineer** (Sep 2023 – Feb 2024)  
  ZValley Technology  
  * Development and testing of the SCRM mobile trading marketing app.

Skills
======
* **Software:** Python, Java, C, MATLAB, R
* **EEG packages:** EEGLAB, BCILAB, MNE, MNE-Python/meegkit
* **Machine Learning:** PyTorch, TensorFlow, ResNet, YOLO, EEGNet

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
