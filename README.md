---

# Challenge 1  
## Environmental Exposure and Birth Outcomes

### Research Question

Does maternal exposure to green and blue spaces influence birth weight and the risk of preterm birth?

### Dataset Overview

- 4,445 mother–child pairs  
- Environmental exposure metrics (NDVI at multiple radii)  
- Distance to green and blue spaces  
- Air pollution indicators (NO₂, PM2.5)  
- Socioeconomic and maternal covariates  
- Outcomes:
  - Birth weight (continuous)
  - Preterm birth (binary)

### Methodology

- Descriptive statistics  
- Group comparisons (t-tests, ANOVA, Chi-square)  
- Pearson correlation analysis  
- Multicollinearity assessment (Variance Inflation Factor)  
- Linear regression for birth weight  
- Logistic regression for preterm birth  
- Best subset selection (AIC, BIC, adjusted R²)  
- 10-fold cross-validation  
- Residual diagnostics  
- Generalized Linear Mixed Models (GLMM)  

### Skills Demonstrated

- Multivariable regression modeling  
- Model diagnostics and assumption checking  
- Feature selection and model comparison  
- Mixed-effects modeling  
- Interpretation in environmental epidemiology  

---

# Challenge 2  
## IOP Variability and Glaucoma Progression

### Research Question

Is long-term intraocular pressure (IOP) variability independently associated with progression to primary open-angle glaucoma (POAG)?

### Dataset Overview

- 819 at-risk patients  
- 10-year follow-up  
- Baseline ocular and systemic covariates  
- IOP variability metrics:
  - Mean IOP
  - Maximum IOP
  - Standard deviation
  - Range
  - Coefficient of variation  
- Outcome:
  - Time-to-POAG progression  

### Methodology

- Descriptive comparisons (progressors vs non-progressors)  
- Correlation matrix for IOP metrics  
- Kaplan–Meier survival curves  
- Log-rank tests  
- Nelson–Aalen cumulative hazard estimation  
- Cox proportional hazards modeling  
- Backward and forward selection  
- Lasso penalized Cox regression  
- Schoenfeld residuals for PH assumption  
- Stratified Cox models  
- Concordance index (cross-validation)  

### Skills Demonstrated

- Survival analysis  
- Time-to-event modeling  
- Penalized regression  
- Model selection strategies  
- Handling proportional hazards violations  
- Clinical risk modeling  

---

# Challenge 3  
## Influenza Vaccine Effectiveness – Causal Inference Framework

### Research Questions

1. What is the causal effect of influenza vaccination on mortality?  
2. Does vaccine effectiveness differ between H1N1- and H3N2-dominated seasons?

### Dataset Overview

- 1,482 hospitalized patients (Australia, 2010–2017)  
- Vaccination status (>14 days before admission)  
- 17 hospitals  
- Extensive comorbidity and demographic variables  
- Outcome:
  - In-hospital survival  

### Methodology

- Crude Average Treatment Effect (ATE) estimation  
- Logistic regression adjustment  
- Mahalanobis matching  
- Optimal matching  
- Propensity Score Matching  
- Inverse Probability of Treatment Weighting (IPTW)  
- Standardized Mean Difference (SMD) balance assessment  
- Kaplan–Meier survival curves  
- Cox proportional hazards modeling  
- Subtype-specific treatment effect analysis  

### Skills Demonstrated

- Causal inference in observational data  
- Confounding adjustment strategies  
- Matching algorithms  
- Propensity score modeling  
- Survival modeling within a causal framework  
- Subgroup treatment effect evaluation  

---

# Technical Stack

- Python 3.x  
- pandas  
- numpy  
- scipy  
- statsmodels  
- lifelines  
- scikit-learn  
- matplotlib  
- seaborn  

---

# Research Competencies Demonstrated

This repository highlights competencies relevant for doctoral research in:

- Clinical epidemiology  
- Biostatistics  
- Survival analysis  
- Causal inference  
- Healthcare data science  
- Translational medical research  

Each project integrates:

- Clearly defined research questions  
- Methodological rigor  
- Appropriate statistical modeling  
- Diagnostic evaluation  
- Clinically grounded interpretation  
- Reproducible Python implementation  
