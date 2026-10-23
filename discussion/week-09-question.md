---
id: w09-wenhao7-tuning-budget-fairness
title: "Is a Fixed Tuning Budget Fair Across SVM Kernels?"
author: wenhao7
---

In Homework 9, we can compare linear, polynomial, and radial SVMs using no more than 20 candidate settings in total. However, these kernel families do not have tuning spaces of the same dimension. A linear SVM mainly requires tuning \(C\), while a radial SVM typically requires tuning both \(C\) and \(\gamma\).

If the radial kernel is given more candidate settings than the linear kernel, does it gain an unfair advantage because it has more opportunities to achieve a low cross-validation error by chance? More generally, when model families have tuning spaces of different sizes, is comparing their minimum CV errors still a fair way to select a kernel? Would equal tuning budgets across kernel families solve the problem, or is a different evaluation strategy needed?
