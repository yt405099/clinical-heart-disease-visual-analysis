# clinical-heart-disease-visual-analysis
Publication-style EDA and clinical visualization of the UCI Heart Disease dataset using Python.

---

## Key Findings
- Heart disease prevalence increases with age, showing a clear distributional shift.  
- Asymptomatic chest pain is associated with a higher proportion of heart disease cases.  
- Exercise-related variables (`thalach`, `oldpeak`) differ substantially between outcome groups.  
- Structural indicators such as `ca` and `thal` show strong visual association with disease presence.  

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
│   ├── fig_01_patient_demographics.png
│   ├── fig_02_age_distribution_by_outcome.png
│   └── ...
├── data/
│   └── heart_disease.csv              # Source dataset
└── requirements.txt                   # Python dependencies
```


![Age Distribution by Heart Disease Outcome](figures/fig_02_age_distribution_by_outcome.png)
![Chest Pain Type vs Heart Disease](figures/fig_04_chest_pain_vs_disease.png)
![Exercise-Induced Indicators Comparison](figures/fig_07_exercise_indicators.png)
---

## Limitations
This is an exploratory analysis based on a small, observational dataset.  
Findings are descriptive and **do not imply clinical causality**.

---

## Tools
Python, pandas, matplotlib, seaborn
