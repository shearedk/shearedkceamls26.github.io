---
layout: project
title: About My Project
permalink: /about-my-project.html

subtitle: "A Study of Reproducibility, Bias, and Equity in Clinical Deep Learning Systems"
project_title: "Predictive Stability vs. Fairness Instability in Clinical ECG Classification: A Multi-Run Analysis of Deep Learning Models"

problem: |
  Artificial intelligence is increasingly being used in healthcare to support clinical decision
  making, especially in areas like ECG-based diagnosis. These systems are designed to help
  clinicians detect heart conditions more efficiently and accurately. However, despite their 
  benefits, these models can unintentionally reinforce or amplify existing healthcare
  disparities across demographic groups such as age and sex. This means that different groups of
  patients may receive unequal diagnostic outcomes even when the same model is used. These 
  issues are particularly concerning in high-stakes medical environments where incorrect
  predictions can directly affect patient care and treatment decisions. As a result, fairness in
  medical AI is not just a technical issue but also a critical ethical and public health concern.
  
  The individuals most affected by this problem are patients from underrepresented or vulnerable
  demographic groups, including older adults and sex-based subpopulations in clinical datasets. 
  Clinicians and healthcare systems are also affected because they rely on these models for 
  decision support, often assuming that performance metrics remain consistent and reliable. If 
  fairness is unstable, then two patients with similar conditions may receive different levels of 
  diagnostic accuracy depending on demographic factors. This creates uncertainty in real-world 
  deployment and raises concerns about trust, safety, and equity in AI-assisted healthcare. It is 
  especially problematic when models appear accurate overall but hide disparities within subgroup 
  performance. Therefore, understanding fairness at a deeper level is essential for responsible 
  clinical AI deployment.

  A key limitation in current research is that fairness is often evaluated as a single measurement 
  from one training run of a model. This approach assumes that fairness metrics such as False 
  Negative Rate or demographic parity remain consistent across experiments, which may not be true 
  in practice. In reality, deep learning models can produce different fairness outcomes each time 
  they are trained due to randomness in initialization, data sampling, and optimization processes. 
  This means that a model may appear fair in one run but unfair in another, even if overall 
  predictive performance such as AUROC remains stable. This gap in understanding makes it 
  difficult to fully trust or validate fairness claims in medical AI systems. This project 
  addresses this limitation by studying fairness stability across multiple training runs in ECG 
  classification models.

approach: |

  - Step 1 — Dataset Preparation: Use the PTB-XL dataset to preprocess clinical ECG signals and organize data by key demographic groups, including age and sex.
  - Step 2 — Model Development in Google Colab: Build deep learning models for multi-label ECG classification using a consistent training pipeline to ensure fair comparison across runs.
  - Step 3 — Multi-Run Experiments: Train and evaluate the same model multiple times to observe variability in predictive performance (such as AUROC) and fairness metrics (such as False Negative Rate across groups).
  - Step 4 — Statistical Analysis: Apply statistical methods, including confidence intervals, to measure and compare stability in predictive performance versus instability in fairness outcomes.
  - Step 5 - Trade-off Evaluation: Analyze relationships between accuracy, fairness, and robustness to understand how improving one aspect may affect others.
  - Step 6 - Communication of Results: Use Overleaf to document findings and prepare a research poster or short paper that clearly presents results and insights.



outcome: |
  By the end of this program, the expected outcome is a fully developed and reproducible research pipeline that evaluates both predictive stability and fairness instability in clinical ECG classification models. This pipeline will allow for systematic multi-run experimentation using the PTB-XL dataset and deep learning frameworks developed in Google Colab.
  The final deliverables will include a research poster and short paper created in Overleaf that summarizes key findings, including evidence of whether fairness metrics remain stable or fluctuate across training runs. The project will also produce visualizations and statistical analyses that highlight trade-offs between predictive performance and fairness. Ultimately, this work aims to contribute to the development of more equitable, reliable, and transparent AI systems for healthcare applications.


final_report_url: https://example.com/your-report.pdf

grad_mentor:
  name: Sudip Sharma
  linkedin: https://www.linkedin.com/in/nxxis/

faculty_mentor:
  name:  Dr. Blessing Ojeme
  linkedin: https://www.linkedin.com/in/blessing-ojeme-phd-259a7342/
---
