# Code for ML-Based Dyslexia Detection Using Incremental Feature Selection on Task-Based fMRI Data

This repository contains the Python scripts and implementation code for the manuscript: **"Optimized Neuro-Computational Diagnostics: Machine-Learning Based Dyslexia Detection Using Incremental Feature Selection on Task-Based fMRI Data."** 

For a detailed explanation of the theoretical background, experimental setup, and neurobiological findings, please refer to the full manuscript. This repository is dedicated to the computational framework, specifically the baseline Random Forest classification and the Incremental Feature Selection (IFS) optimization algorithms.

## Title of the Dataset
**MorphoSem (fMRI task reading)**
* **Accession Number:** ds004786
* **Version:** 1.0.0
* **Data Availability:** This is an open-source dataset freely available on the OpenNeuro repository. 
* **Download Link:** [https://openneuro.org/datasets/ds004786/versions/1.0.0](https://openneuro.org/datasets/ds004786/versions/1.0.0)

*(Note: To replicate this study, please download the preprocessed NIfTI files from the OpenNeuro link above and place them in your local data directory before running the scripts).*

## Repository Structure

The core implementation files are located in the `Codes/` directory:

```text
├── Codes/                    
│   ├── 1-Inferior_Frontal_Gyrus 
│   	├── Generate_ROIs_Inferior_Frontal_Gyrus.ipynb
│   ├── 2-Superior_Temporal_Gyrus 
│   	├── Generate_ROIs_Superior_Temporal_Gyrus.ipynb
│   ├── 3-Middle_Temporal_Gyrus 
│   	├── Generate_ROIs_Middle_Temporal_Gyrus.ipynb
│   ├── 4-Inferior_Temporal_Gyrus 
│   	├── Generate_ROIs_Inferior_Temporal_Gyrus.ipynb
│   ├── 5-Supramarginal_Gyrus 
│   	├── Generate_ROIs_Supramarginal_Gyrus.ipynb
│   ├── 6-Angular-Gyrus 
│   	├── Generate_ROIs_Angular-Gyrus.ipynb
│   ├── 7-Temporal_Fusiform_Cortex 
│   	├── Generate_ROIs_Temporal_Fusiform_Cortex.ipynb
│   ├── 8-Occipital_Fusiform_Gyrus 
│   	├── Generate_ROIs_Occipital_Fusiform_Gyrus.ipynb
│   ├── 9-IFS_[RF] 
│   	├── Feature_Select_[RF].ipynb
└── requirements.txt        # Required Python libraries (e.g., nilearn, nibabel, scikit-learn, pandas)
└── README.md               # Repository documentation
