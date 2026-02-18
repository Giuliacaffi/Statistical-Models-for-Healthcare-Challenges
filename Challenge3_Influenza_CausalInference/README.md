# Challenge 3 – Influenza Vaccine Effectiveness (Causal Inference)

## Title
Evaluating Influenza Vaccine Effectiveness Against Mortality Using a Causal Inference Framework

## Research Questions

1. What is the causal effect of influenza vaccination on in-hospital mortality?
2. Does vaccine effectiveness differ between H1N1- and H3N2-dominated seasons?

## Background

Observational vaccine effectiveness studies are prone to confounding. High-risk patients are more likely to be vaccinated and also more likely to die, creating bias. Causal inference methods allow estimation of treatment effects under observational settings.

---

## Dataset

- 1,482 hospitalized influenza patients (Australia, 2010–2017)
- Vaccinated if >14 days before admission
- 17 hospitals
- Extensive comorbidity and demographic covariates
- Outcome:
  - In-hospital survival (0 = died, 1 = survived)

---

## Methods

### Crude Analysis
- Unadjusted mortality comparison

### Regression Adjustment
- Multivariable logistic regression

### Matching Approaches
- Mahalanobis matching
- Optimal matching
- Propensity score matching

### Weighting Approach
- Inverse Probability of Treatment Weighting (IPTW)

### Balance Diagnostics
- Standardized Mean Differences (SMD)

### Survival Modeling
- Kaplan–Meier curves
- Cox proportional hazards models
- Subgroup analysis by influenza subtype dominance

---

## Key Findings (Summary)

- Crude analysis suggested limited vaccine effect.
- Adjusted and matched models showed protective association.
- Results varied slightly between subtype-dominant seasons.
- Residual confounding cannot be excluded.

---

## Skills Demonstrated

- Causal inference methods
- Propensity score modeling
- Matching algorithms
- IPTW
- Survival modeling within a causal framework
- Confounding assessment
