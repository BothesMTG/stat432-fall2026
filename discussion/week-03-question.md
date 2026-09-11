---
id: w03-wenhao7-gcv-loocv-leverage
title: "When Can GCV Differ from LOOCV?"
author: wenhao7
---------------

For ridge regression, LOOCV uses the individual diagonal leverage values $(\mathbf H\_\lambda)*{ii}$, while GCV replaces them with their average, $\operatorname{tr}(\mathbf H*\lambda)/n$.

Under what condition would GCV and LOOCV give exactly the same error criterion for a fixed ridge smoother? What might happen when a few observations have much higher leverage than the others? Could GCV then select a substantially different value of $\lambda$ from LOOCV, and is the direction of that difference predictable?
