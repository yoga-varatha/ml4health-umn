---
layout: page
title: Calendar
description: Listing of course modules and topics.
---

# Calendar
**RR**{: .label .label-red }: Required reading  **AR**{: .label .label-blue }: Additional reading

{% for module in site.modules %}
{{ module }}
{% endfor %}

| Week | Date | Lecture | Date | Lecture |  
| -----|------|---------|------|-------- |  
| 1 | 1/15 | Holiday | 1/17 | Intro to class |  
| 2 | 1/22 | What’s different in health? modalities, imbalance, rare events, stakeholders, etc. [[scribe-1]](../_files/lec2_scribe1.pdf)[[scribe-2]](../_files/lec2_scribe2.pdf)| 1/24 | Intro to clinical care and understanding clinical data [[scribe-1]](../_files/lec3_scribe1.pdf)|  
| 3 | 1/29 | Classification methods in healthcare: diagnosis, prognosis, stratification, segmentation | 1/31 | Intro to numpy, pandas, sklearn (**Lab 0**) |  
| 4 | 2/5 | SVM, random forests, xgboost: interpretation of different model choices | 2/7 | Unsupervised methods for healthcare: subtype discovery, pattern discovery (**MP1 - omics**) |  
| 5 | 2/12 | PCA, ICA, tensor decomposition | 2/14 | Clustering methods (**Deadline to form project groups**)|  
| 6 | 2/19 | Causal Inference in Healthcare | 2/21 | Digital health (Guest Lecture - Prof. Srivastava) (**MP2 – physiological signals**) |  
| 7 | 2/26 | Deep learning for healthcare: Intro | 2/28 | ConvNets & PyTorch tutorial (**Project proposals**)|  
| 8 | 3/4 | Spring Break | 3/6 | Spring Break |  
| 9 | 3/11 | CNNs for medical imaging and signals | 3/13 | Explanations and attributions (**MP3 - medical imaging**)|  
| 10 | 3/18 | Machine learning for medical imaging: (Guest lecture - Google Health) | 3/20 | Graphs and graph neural networks in healthcare |  
| 11 | 3/25 | Sequence modeling in healthcare - HMMs to RNNs – health applications | 3/27 | Guest Lecture: ML for Mental Health (**Project mid-term reports**)|  
| 12 | 4/1 | Learning health systems (Guest Lecture - M Health Fairview) | 4/3 |  Unsupervised deep learning for healthcare, self-supervised learning (**MP4 – clinical text**) |  
| 13 | 4/8 | Generative models in healthcare | 4/10 | AI evaluation and deployment (Guest Lecture - Institute for Health Informatics) |  
| 14 | 4/15 | Clinical foundation models | 4/17 | Lab on large language models |  
| 15 | 4/22 | Ethical AI for healthcare (Guest Lecture - Mayo Clinic) | 4/24 | Trustworthy Health AI - Robustness and Reliability |  
| 16 | 4/29 | **Project presentations** |  EOS | **Reports due** |  
