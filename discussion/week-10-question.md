---
id: w10-wenhao7-mtry-correlation
title: "Why Doesn't Lower Tree Correlation Always Help?"
author: wenhao7
---

Lowering `mtry` generally makes the trees in a random forest less similar, so averaging them may benefit from greater diversity. However, a smaller candidate-predictor set can also make strong predictors unavailable at some splits, weakening the individual trees. Why does lower tree-to-tree correlation alone therefore not guarantee lower forest prediction error? Please explain the trade-off between tree diversity and individual-tree predictive strength, using a bias-variance interpretation or a small conceptual counterexample if helpful.
