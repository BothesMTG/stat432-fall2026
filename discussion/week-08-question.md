---
id: w08-wenhao7-nonsupport-boundary
title: "When Does a Non-Support Vector Begin to Affect the SVM Boundary?"
author: wenhao7
---

The lecture explains that observations with \(\alpha_i=0\) are not support vectors, so moving a point that is far outside the margin slightly should not change the fitted SVM boundary.

Suppose we continuously move one non-support vector toward the decision boundary while keeping all other observations fixed. At what point should we expect the fitted boundary to begin changing? Does the point first need to reach the margin and become a support vector, or can the optimal boundary start moving before that happens? How can this be explained using the SVM constraints and the dual coefficients \(\alpha_i\)?
