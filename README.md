# Guidance on Individualized Treatment Rule Estimation in High Dimensions
> Contributed Poster Presented at ACIC 2025

## Authors

- Philippe Boileau, McGill University
- Ning Leng, Genentech Inc
- Sandrine Dudoit, University of California, Berkeley

## Abstract

Individualized treatment rules, cornerstones of precision medicine, inform
patient treatment decisions with the goal of optimizing patient outcomes. These
rules are generally unknown functions of patients' pre-treatment covariates,
meaning they must be estimated from clinical or observational study data. Myriad
methods have been developed to learn these rules, and these procedures are
demonstrably successful in traditional asymptotic settings with moderate number
of covariates. The finite-sample performance of these methods in
high-dimensional covariate settings, which are increasingly the norm in modern
clinical trials, has not been well characterized, however. We perform a
comprehensive comparison of state-of-the-art individualized treatment rule
estimators, assessing performance on the basis of the estimators' rule quality,
interpretability, and computational efficiency. Sixteen data-generating
processes with continuous outcomes and binary treatment assignments are
considered, reflecting a diversity of randomized and observational studies. We
summarize our findings and provide succinct advice to practitioners needing to
estimate individualized treatment rules in high dimensions. Owing to these
estimators' poor interpretability, we propose a novel pre-treatment covariate
filtering procedure based on recent work for uncovering treatment effect
modifiers. We show that it improves estimators' rule quality and
interpretability. All code is made publicly available, facilitating
modifications and extensions to our simulation study.
