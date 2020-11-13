---
layout: left-menu
title: Partial concurrent adjustment → Estimate regression coefficients + Last outliers
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial concurrent adjustment → Estimate regression coefficient +
Last outliers* strategy means that **the ARIMA model, outliers and other
regression variables are not re-identified, except the
outliers in the last year of the series**. Indeed, JDemetra+ has a
test procedure to detect outliers.

Additionally to that « outlier-refreshment », all coefficients of
the RegARIMA model are re-estimated. The transformation type remains
unchanged.

The example below shows the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Estimate regression coefficient + Last outliers* option
**(right)**. Both **ARIMA and regression coefficients have
been re-estimated**. However, **the number of estimated coefficients in
the revised model is larger** than in the initial model because an
additional outlier has been identified in the last year of the data
span (the level shift in January 2017).

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage26.jpg)

{: .text-center.small}

**The *Partial concurrent adjustment* → *Estimate regression coefficient + Last outliers* revision policy results**