
# Computational Notebooks – Internship Report

This repository contains the Jupyter notebooks used for data cleaning, preprocessing, classification, and exploratory analysis for the academic internship report:

Monitoring & Evaluation of Health and Agriculture Projects at ADPP Mozambique

The notebooks document the analytical workflow underlying the results presented in the report. They are provided to ensure transparency and reproducibility of the computational steps.

⸻

## Repository Contents

The repository consists exclusively of Jupyter notebooks (.ipynb).
Notebooks are numbered to indicate the intended execution and reading order.

**Notebook Description**
1_g1_full_clean.ipynb:	Full cleaning and harmonisation of questionnaire G1
2_q456_full_clean.ipynb:	Cleaning and merging of Q4–Q6 instruments
3_q1_Classifier.ipynb:	Supervised classification of open-ended responses (Q1)
4_phase_1.ipynb:	Feature engineering and initial model iteration
5_ML.ipynb:	Final model training, evaluation, and error analysis


⸻

## Execution Order

The notebooks are intended to be read and executed sequentially following the numerical prefix in each filename (1–5).
Later notebooks depend on intermediate outputs generated in earlier stages.

⸻

## Data Availability

Raw data are not included in this repository due to data protection and confidentiality constraints related to project beneficiaries.

Variable names, transformations, and intermediate outputs correspond exactly to those referenced in the written report and its appendices.

⸻

## Software Environment

The analysis was conducted using Python (Jupyter Notebook environment).
Core libraries include standard data science and machine learning packages (e.g. pandas, numpy, scikit-learn).

Exact package versions are not fixed, as the notebooks are provided for documentation and transparency rather than automated re-execution without access to the underlying data.

⸻

## Relation to Written Report

These notebooks support the methods and results presented in the internship report.
They are referenced in Appendix D: Notebooks, which provides a structured overview for academic review.

The notebooks are not intended to function as standalone analytical products without the contextual explanation provided in the report.

⸻

## Notes on Use

The notebooks reflect an applied Monitoring and Evaluation workflow developed in a real-world NGO context.
They prioritize interpretability, traceability, and practical feasibility over model optimisation.
