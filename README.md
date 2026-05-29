# Machine Learning Prediction of PAM50 Subtypes in HR- Breast Cancer

[![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Gradio](https://img.shields.io/badge/gradio-4.0-orange.svg)](https://gradio.app/)

## Overview

This repository contains the complete code and analysis for my Master's thesis:

**"Machine Learning Prediction of PAM50 Subtypes in Hormone Receptor Negative (HR-) Breast Cancer from Gene Expression"**

*Author:* Amat Cham  
*Supervisor:* Prof. Dr. Adrian Crăciun  
*Institution:* West University of Timișoara, Faculty of Computer Science  
*Programme:* Master's in Bioinformatics  
*Year:* 2026

## Abstract

Breast cancer is molecularly diverse, making accurate subtype classification vital for prognosis and treatment guidance. This project builds a leakage-safe supervised machine learning pipeline to predict PAM50 subtypes from curated TCGA-BRCA gene expression data, with a focus on hormone receptor-negative (HR-) disease.

## Key Findings

| Model | Accuracy | Balanced Accuracy | Macro F1 | Macro AUC |
|-------|----------|-------------------|----------|-----------|
| **Logistic Regression** | **90.1%** | **90.0%** | **0.912** | **0.986** |
| XGBoost | 89.6% | 84.1% | 0.876 | - |
| SVM RBF | 89.6% | 83.3% | 0.860 | - |
| CatBoost | 88.0% | 77.2% | 0.821 | - |

### Top Predictive Genes

| Gene | Importance |
|------|------------|
| CEP55 | 0.107 |
| MELK | 0.107 |
| HER2IHCscore | 0.105 |
| SFRP1 | 0.102 |
| ESR1 | 0.097 |

### Clinical Translation

| Pathway | Count | Percentage |
|---------|-------|------------|
| TNBC Chemotherapy-Oriented | 320 | 84.7% |
| HER2-Targeted Review | 32 | 8.5% |
| Non-Basal HR- Review | 23 | 6.1% |
| Discordant HER2 Reassessment | 3 | 0.8% |

## Repository Structure
