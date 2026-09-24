---
id: w05-wenhao7-correlated-predictors
title: "Remove Highly Correlated Predictors Before KNN?"
author: wenhao7
---

Should highly correlated predictors be removed before applying KNN, or can keeping them sometimes improve prediction?

Suppose two predictors in a KNN model are highly correlated but not exactly identical. Keeping both may effectively give their shared information extra weight in the distance calculation and change which observations are selected as nearest neighbors. However, removing one predictor could also discard useful information that is not completely duplicated.

Is high correlation alone enough to justify removing one of the predictors? In particular, could keeping both sometimes help when the shared information is especially important for predicting the response, even though that information is implicitly weighted more heavily? Explain when redundancy might hurt KNN and when it might help.
