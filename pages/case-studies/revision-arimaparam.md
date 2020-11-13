---
layout: left-menu
title: Partial concurrent adjustment → Estimate regression coefficients + Arima parameters
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial concurrent adjustment → Estimate regression coefficient +
Arima parameters* strategy means that **the ARIMA model, outliers and
other regression variables are not re-identified**. Every
coefficient of the RegARIMA model is re-estimated but the
explanatory variables and ARIMA orders remain the same. The
transformation type remains unchanged.

The example below shows the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Estimate regression coefficient + Arima parameters* option
**(right)**. The **ARIMA and regression coefficients have been
re-estimated**, thus the number of estimated coefficients in the
revised model is the same as in the initial model (i.e. 16 estimated
parameters). The transformation type and model structure remain
unchanged while all coefficients have been updated.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage25.jpg)

{: .text-center.small}

**The *Partial concurrent adjustment* → *Estimate regression coefficients + Arima parameters* revision policy results**



