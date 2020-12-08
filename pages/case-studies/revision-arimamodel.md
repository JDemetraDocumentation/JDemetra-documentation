---
layout: left-menu
title: Partial concurrent adjustment → Estimate regression coefficients + Arima model
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial concurrent adjustment → Estimate regression coefficient +
Arima model* option means that **the ARIMA model and all the regression
variables are re-identified, except the calendar variables.
All parameters are re-estimated and the transformation type remains
unchanged**.

The example below shows the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Estimate regression coefficient + Arima model* option
**(right)**. The ARIMA orders have been re-identified (from
(2,1,0)(0,1,1) to (0,1,1)(1,1,1)), as well as all outliers (hence the
lack of prespecified outliers section). A mean effect has also been
automatically detected and added to the regression variables. All coefficients have been re-estimated.


{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UG_PCA_image1.jpg)

{: .text-center.small}

**The *Partial concurrent adjustment* → *Estimate regression coefficient + Arima model* revision policy results**
