---
id: w02-wenhao7-cv-selection-leakage
title: "Predictor Selection Before Cross-Validation"
author: wenhao7
---

Suppose we use the full dataset to choose predictors first, but then refit the selected model separately inside each cross-validation training fold. Is the resulting cross-validation error still a valid estimate of out-of-sample performance? If not, what information has leaked into the validation folds?
