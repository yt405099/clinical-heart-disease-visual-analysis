# clinical-heart-disease-visual-analysis
Publication-style EDA and clinical visualization of the UCI Heart Disease dataset using Python.

---

## Key Findings
- 
-   
-  
- 

---

## Dataset
- Source: UCI Heart Disease (Cleveland subset)  
- Observations: 303  
- Variables: 14  
- Outcome: `num` binarized into no disease (0) vs disease (≥1)

---
## Repository Structure
```
heart-disease-clinical-eda/
├── heart_disease_clinical_eda.ipynb   # Main analysis notebook
├── README.md                          # Project overview and findings
├── figures/                           # Saved publication-quality figures
│   ├── fig_0_age_by_outcome.png
│   ├── fig_02_cp_by_outcome.png
│   ├── fig_03_exang_by_outcome.png
|   ├── fig_04_thalach_kde.png
|   ├── fig_05_oldpeak_box.png
|   ├── fig_06_ca_by_outcome.png
├── data/
│   └── heart_disease_uci.csv          # Source dataset
└── requirements.txt                   # Python dependencies
```


![Age by Heart Disease Outcome](figures/fig_01_age_outcome.png)
![Chest Pain Type by Heart Disease Outcome](figures/fig_02_cp_by_outcome.png)
![ST-Depression by Heart Disease Outcome](figures/fig_04_oldpeak_box.png)
---

## Limitations
This is an exploratory analysis based on a small, observational dataset.  
Findings are descriptive and **do not imply clinical causality**.

---

## Tools
Python, pandas, matplotlib, seaborn
