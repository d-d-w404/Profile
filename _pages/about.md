---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm **Wendeng Wang**.

I am a Master's student in Electrical and Computer Engineering at the University of California, San Diego (UCSD), conducting research at the Swartz Center for Computational Neuroscience (SCCN) under the supervision of Prof. Tzyy-Ping Jung.

My research interests span Neuro-AI, brain-computer interfaces, neural representation learning, and intelligent systems. I develop [pyorica](https://github.com/goodshawn12/pyorica) for online source separation, neural decoding, and automated artifact removal, with the long-term goal of building intelligent systems that can better understand human brain activity.

Beyond neuroscience, I am also interested in computer vision and machine learning. Previously, I contributed to the development of a core vision framework for [shootz](https://www.shootz.tech/) and trained deep learning models for object detection, image classification, and person re-identification using architectures such as YOLO, ResNet, and ReID-based methods.

More broadly, I am interested in bridging neuroscience and artificial intelligence through representation learning, multimodal AI, and next-generation Neuro-AI systems.

## Education

* **M.S.** in Electrical and Computer Engineering, University of California, San Diego (UCSD), Sep 2024 – Jun 2026  
  GPA: 3.641/4.0
* **B.S.** in Computer Science, Central South University (CSU), Sep 2019 – Jun 2023  
  GPA: 88.69/100  
  Scholarships: National Scholarship (0.2%)

## Research Experience

**LLM-Agent for Cross-Platform Automated EEG Analysis**  
*SCCN Lab, UCSD · Apr 2026 – Present*

* Developed and encapsulated standardized EEG analysis skills within an open Agent framework, enabling LLMs to orchestrate high-performance signal processing algorithms via Function Calling.
* Formulated evaluation frameworks and guardrails for critical EEG contexts, minimizing hallucinations and mis-triggers through edge-case testing.


**Validation of a Real-Time EEG Artifact Removal Pipeline Based on ASR, ORICA, and ICLabel**  
*SCCN Lab, UCSD · Feb 2026 – present*

* Implemented and evaluated the Online Recursive ICA (ORICA) algorithm in Python.
* Engineered a production-ready package integrating ASR, ORICA, and extended ICLabel for real-time artifact removal and source visualization.
* Validated the pipeline across multiple EEG datasets under diverse subject profiles and noise environments.

**A Closed-Loop Real-Time EEG Framework with Adaptive Denoising and Online Learning for Emotion Classification**  
*SCCN Lab, UCSD · April 2025 – Oct 2025*  
*[12th International IEEE EMBS Conference on Neural Engineering (NER 2025), San Diego, CA · Nov 2025](https://cmsworkshops.com/NER2025/view_paper.php?PaperNum=1759)* · [Download poster (PDF)](https://d-d-w404.github.io/Profile/files/wang-realtime-eeg-poster.pdf)

**CNN-Based Framework for Automated Athlete Motion Classification**  
*[Shootz](https://www.shootz.tech/), Central South University · Jun 2022 – Jun 2023*

* [Tools](https://github.com/d-d-w404/Sports_Annotation_Tool) for key-frame extraction and targets annotation in sports videos.
* Automated basketball video classification [framework](https://github.com/d-d-w404/AMA) Based on ResNet18, YOLOv5, and ReID.



## Open Source Project

**[pyorica](https://github.com/goodshawn12/pyorica)**  
*SCCN Lab, UCSD · Apr 2026 – Present*
* Online pipeline: bandpass IIR → ASR → ORICA → ICLabel artifact rejection → sensor-space reconstruction
* Real-time ready: LSL streaming + chunk-wise ORICA (no full-session refit)
* Benchmarking: simulated real-time runs on multi-subject EEG with per-IC source energy metrics
* Reproducibility: PipelineConfig / YAML workflows for cross-session evaluation

## Work Experience

**Research Assistant**  
*SCCN Lab, UCSD · Feb 2025 – Present*

* Implemented a Python real-time EEG artifact removal system using ORICA and ICLabel.
* Worked on real-time stress and emotion detection based on EEG signals.
* Assisted with EEG data collection in movement and VR environments.

**Machine Learning Engineer (Core Developer)**  
*Shootz, Central South University · Jun 2022 – Sep 2023*

* Led development of a data annotation tool and automation framework for large-scale visual datasets.
* Responsible for dataset labeling, deep learning model training for computer vision, and demo implementation.

**Software Development Engineer**  
*ZValley Technology · Sep 2023 – Feb 2024*

* Contributed to the development and testing of the SCRM system, a mobile trading marketing app designed to streamline user transactions.

[Download full CV (PDF)](https://d-d-w404.github.io/Profile/files/wendeng-wang-cv.pdf)
