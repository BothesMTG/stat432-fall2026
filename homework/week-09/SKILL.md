---
name: svm-analysis
description: Rigorous, leak-free SVM classification workflow covering data suitability, justified kernel selection, hyperparameter tuning, evaluation, and compact reporting.
disable-model-invocation: true
---

When invoked, guide the SVM workflow through these rigorous steps:
1. **Suitability Assessment**: Conclude whether SVM is a sensible choice based on sample size, predictor-to-sample ratio, and response structure. Verify binary/multiclass classification targets, address missing values, and encode categorical predictors.
2. **Justified Kernel Selection**: Select candidate kernels (e.g., linear, RBF) and **explicitly justify why** each kernel fits the underlying feature space geometry or data characteristics.
3. **Hyperparameter Design & Tuning**: Identify tuning parameters (e.g., $C$, $\gamma$) and state which parameters are held fixed. Use **identical resampling splits** across all candidates. Ensure all preprocessing (e.g., scaling) is fitted strictly within each training fold to prevent data leakage.
4. **Model Evaluation Strategy**: Select a performance metric aligned with the prediction objective (avoiding generic imbalance assumptions). Clearly separate hyperparameter tuning from final unbiased performance evaluation.
5. **Tabulation & Visualization**: Require a compact comparison table and a tuning-performance figure that directly support model-selection evidence.
6. **Interpretation & Results**: Interpret the final fit by reporting key numerical results (e.g., test error, AUC, support vector proportion) while avoiding over-interpreted causal feature impacts.
7. **Evidence Prioritization**: Prioritize core justifying evidence to ensure the final report fits strictly within a single printed page at 11-point font.
