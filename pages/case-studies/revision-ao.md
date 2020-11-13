---
layout: left-menu
title: Current adjustment (AO approach)

tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---

The *Current adjustment (AO approach)* strategy means that **the ARIMA
model, outliers and other regression variables are not re-identified and
the values of the associated coefficients are fixed**. The transformation
type also remains unchanged.

**All new observations are automatically classified as additive outliers**
and corresponding coefficients are estimated during the regression
phase. This does not impact the other variables' coefficient estimation
(they are fixed). The new observations are processed as intervention
variables and the AO statuses will last till the next concurrent
refreshment.

The example below shows the initial model **(left)** and the results of
the refreshment procedure with the *Current adjustment (AO approach)*
option **(right)**. No element of the previous model has changed except all
coefficient values are now fixed, hence the absence of p-values, scores
and of the correlation of estimates matrix in the *Summary*. The original
outlier (April 2006) is still in the refreshed model, with its fixed
coefficient (its status went from "pre-specified to "fixed"). The only
difference is the addition of an intervention variable for the added
month, September 2020. It can be seen at the end of the *Summary* and in
the *Regressor* panel.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/Summary.jpg)

{: .text-center.small}

**The comparison of the results from the initial nad refreshed models**

Display-wise, there is an additional change. For the initial model the regressiors are displayed in the *Regression* panel.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/Last_outlier_regressors.jpg)

{: .text-center.small}

**The *Regressor* panel for the initial model**

For the model refreshed with the the *Current adjustment (AO approach)* the *Regressor* panel does
not contain any of the previous regressors (because they are fixed).
However, it is easy to verify via the *Summary* that they are still in the
model.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/Current_AO_regressors.jpg)

{: .text-center.small}

**The *Regressor* panel for the refreshed model**