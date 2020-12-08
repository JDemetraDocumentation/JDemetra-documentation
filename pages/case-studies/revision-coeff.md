---
layout: left-menu
title: Partial concurrent adjustment → Estimate regression coefficients
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial current adjustment → Estimate regression coefficients*
option means that **the ARIMA model, outliers and other regression
variables are not re-identified. The coefficients of the ARIMA model
are fixed, but the regression coefficients are re-estimated**.

In particular, **new outliers cannot be added** to the model and
**neither calendar variables nor the outliers type can be changed. The
transformation type remains unchanged**.

The example below shows the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Estimate regression coefficients* option **(right)**. The
number of estimated parameters is 16 in the initial model and 14 in the
revised model. That is because the ARIMA coefficients are not
estimated.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage24.jpg)

{: .text-center.small}

**The *Partial concurrent adjustment* *→ Estimate regression coefficients* revision policy results**

