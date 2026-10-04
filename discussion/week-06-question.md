---
id: w06-wenhao7-bayes-cutoff
title: "Bayes Cutoff Under Class Imbalance"
author: wenhao7
---

In an imbalanced classification problem where positive cases are rare, people often suggest lowering the cutoff below 0.5 to detect more positives. Suppose the fitted probability is a well-calibrated estimate of $P(Y=1\mid X=x)$, and false positives and false negatives have equal costs. Is class imbalance alone a reason to change the Bayes cutoff from 0.5? If not, what additional assumptions, such as unequal error costs, would justify using a different cutoff?
