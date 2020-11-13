---
layout: left-menu
title: Partial concurrent adjustment → Estimate regression coefficients + outliers
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
The *Partial concurrent adjustment → Estimate regression coefficient +
outliers option* means that **while** the ARIMA model and regression
**variables** are not re-identified, **the outliers are, and on the
whole series span**. **Moreover, all coefficients** are re-estimated.
The transformation type remains unchanged.

The **example** below **shows** the initial model **(left)** and the
results of the refreshment procedure with the *Partial concurrent
adjustment → Estimate regression coefficient + outliers* option
**(right)**. **Again, both** **ARIMA and regression variables
coefficients have been re-estimated**. In the revised model, there is no
Prespecified outliers section **because they have all been
re-identified.**

{: .text-center.image-wrapper}

![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage27.jpg)

{: .text-center.small}

**The *Partial concurrent adjustment* → *Estimate regression coefficient + outliers* revision policy results**

