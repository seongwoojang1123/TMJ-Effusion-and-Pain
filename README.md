# Relationship Between MRI-Detected TMJ Effusion and Pain Intensity in Temporomandibular Disorder Patients

This repository contains the analysis code for the study **"Relationship Between MRI-Detected TMJ Effusion and Pain Intensity in Temporomandibular Disorder Patients."**

The project focuses on the relationship between MRI-detected temporomandibular joint (TMJ) effusion and pain intensity in patients with temporomandibular disorders (TMD). The repository is organized to help users follow the full workflow from data preprocessing to descriptive analysis, logistic regression modeling, and feature significance analysis.

Unlike image-based deep learning repositories, this project is centered on **structured clinical data analysis** and **interpretable statistical / machine learning pipelines**. The main analytical goals are:

- to compare pain-related clinical characteristics according to TMJ effusion status
- to evaluate TMJ effusion grade as an ordinal clinical outcome
- to assess the discriminative performance of clinical variables for predicting effusion presence and effusion grade
- to perform exploratory sensitivity analyses for class imbalance


---

## Project Overview

TMJ effusion is commonly regarded as an MRI finding related to intra-articular inflammatory activity, but its clinical relationship with pain intensity remains inconsistent across studies. This repository provides code for a structured analysis pipeline designed to examine that relationship using clinical variables and MRI-based effusion labels.

The repository includes:

- preprocessing of clinical and MRI-derived labels
- descriptive analysis of demographic and clinical variables
- binary logistic regression for effusion absence vs presence
- multiclass / ordinal-oriented analysis for effusion grade (0/1/2)
- ROC and AUROC-based evaluation with bootstrap confidence intervals
- exploratory class imbalance handling using SMOTE
- feature-level interpretation of clinically relevant predictors

---

## Repository Structure

- `1_data_preprocessing_Effusion.ipynb`  
  Data cleaning, variable selection, missing-value handling, and label preparation.

- `2_data_initial_analyze_Effusion.ipynb`  
  Descriptive statistics, baseline comparisons, and subgroup distribution analysis.

- `3_Logistic_Regression_Training_Effusion.ipynb`  
  Logistic regression modeling, ROC/AUROC evaluation, bootstrap confidence intervals, and SMOTE-based sensitivity analysis.

- `4_feature_significance_analysis_Effusion.ipynb`  
  Interpretation of clinically relevant predictors and feature significance.

- `README.md`  
  Project overview, workflow summary, and usage guidance.


