# Challenge 1 – Environmental Exposure and Birth Outcomes

## Title
Exploring the Impact of Green and Blue Spaces on Birth Outcomes

## Research Question

Does maternal exposure to natural environments (green and blue spaces) influence birth weight and the risk of preterm birth?

## Background

Environmental exposure during pregnancy has been associated with fetal development and perinatal outcomes. Natural environments may reduce stress, improve air quality, and promote healthier behaviors. However, associations may be confounded by socioeconomic and demographic factors.

This study evaluates both continuous and binary birth outcomes using multivariable regression frameworks.

---

## Dataset

- 4,445 mother–child pairs
- Environmental exposure metrics:
  - NDVI (100m, 300m, 500m buffers)
  - Distance to green spaces
  - Distance to blue spaces
- Air pollution indicators:
  - NO₂
  - PM2.5
- Maternal covariates:
  - Age
  - Education
  - Smoking
  - BMI
  - Socioeconomic indicators
- Outcomes:
  - Birth weight (continuous)
  - Preterm birth (binary)

---

## Methods

### Exploratory Data Analysis
- Summary statistics
- Distribution visualization
- Group comparisons (t-test, ANOVA, Chi-square)
- Correlation matrix

### Multicollinearity Assessment
- Variance Inflation Factor (VIF)
- Removal of highly collinear predictors

### Modeling Strategy

**Birth Weight**
- Multiple linear regression
- Best subset selection (AIC, BIC, adjusted R²)
- 10-fold cross-validation
- Residual diagnostics (normality, homoscedasticity)

**Preterm Birth**
- Logistic regression
- Odds ratios with confidence intervals
- Model comparison via AIC
- Cross-validation

### Mixed Effects Modeling
- GLMM to account for clustering within cohort

---

## Key Findings (Summary)

- Green space exposure showed modest associations with birth weight.
- Effects attenuated after adjusting for socioeconomic confounders.
- Air pollution demonstrated stronger and more consistent associations.
- No robust independent association was found for blue space exposure.

---

## Skills Demonstrated

- Multivariable regression modeling
- Model diagnostics
- Feature selection strategies
- Mixed-effects modeling
- Epidemiological interpretation
