---
layout: left-menu
title: Concurrent adjustment
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---

According to (ou as defined in?) the *ESS Guidelines on Seasonal
Adjustment* (2015), concurrent adjustment means that **every time a new
observation is available,** the model, filters, outliers, regression
variables and transformation type are re-identified and the
**corresponding** **coefficients** and factors are re-estimated.
**This means that the previous specification and results are wiped off
and that the adjustment process is started again from scratch.**

The **example** below **shows** the initial model **(left)** and the
results of the refreshment procedure with the *Concurrent adjustment*
option **(right)**. The transformation type has changed from none to log
**and** the ARIMA orders have been re-identified (from (0,1,1)(1,1,0) to
(1,1,0)(0,1,1)). The **regression model has also changed:** trading days
and leap year are considered irrelevant for this series, and the number
of outliers has drastically reduced.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UG_PCA_image2.jpg)

{: .text-center.small}

**The *Concurrent adjustment* revision policy results**