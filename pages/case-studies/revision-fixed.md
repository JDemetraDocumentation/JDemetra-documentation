---
layout: left-menu
title: Partial concurrent adjustment → Fixed model
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial concurrent adjustment → Fixed model* strategy means that
the ARIMA model, outliers and other regression **variables are not
re-identified and the values of the associated coefficients are
fixed**. In particular, **new outliers cannot be added** to the model and
**neither calendar variables nor the outliers type** can be changed. The
transformation type remains unchanged.

The example below shows the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Fixed model* option **(right)**. The ARIMA orders are
not re-estimated and the associated coefficients are the
same as before. The trading days variables and outliers are fixed
too and no new regression effect is identified.

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage23.jpg)

{: .text-center.small}

**A *Partial concurrent adjustment* → *fixed model* revision policy results**