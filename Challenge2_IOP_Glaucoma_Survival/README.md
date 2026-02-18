# Challenge 2 – IOP Variability and Glaucoma Progression

## Title
Investigating the Role of Intraocular Pressure Variability in Primary Open-Angle Glaucoma

## Research Question

Is long-term intraocular pressure (IOP) variability independently associated with progression to primary open-angle glaucoma (POAG)?

## Background

Elevated intraocular pressure is a known risk factor for glaucoma. However, the independent role of long-term IOP variability remains controversial. Survival analysis methods allow modeling of time-to-event data while accounting for censoring.

---

## Dataset

- 819 at-risk patients
- 10-year follow-up
- Baseline ocular and systemic characteristics
- IOP metrics:
  - Mean IOP
  - Maximum IOP
  - Standard deviation
  - Range
  - Coefficient of variation
- Outcome:
  - Time to POAG progression

---

## Methods

### Exploratory Analysis
- Comparison between progressors and non-progressors
- Correlation analysis of IOP metrics

### Survival Analysis

- Kaplan–Meier curves
- Log-rank test
- Nelson–Aalen cumulative hazard

### Cox Proportional Hazards Models

- Univariate Cox models
- Multivariable Cox regression
- Backward and forward selection
- Lasso-penalized Cox regression
- Schoenfeld residuals for proportional hazards assumption
- Stratified Cox models when PH assumption violated

### Model Evaluation

- Concordance index
- Cross-validation

---

## Key Findings (Summary)

- IOP variability metrics were strongly correlated.
- Mean IOP remained the most stable independent predictor.
- Variability measures lost significance after multivariable adjustment.
- Penalized models confirmed redundancy among variability metrics.

---

## Skills Demonstrated

- Survival analysis
- Cox proportional hazards modeling
- Penalized regression
- Assumption checking
- Clinical risk interpretation
