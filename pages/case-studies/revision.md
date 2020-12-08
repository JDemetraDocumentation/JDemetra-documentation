---
layout: left-menu
title: Revision policies

tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
---
Saved seasonal adjustment results from multi-processing can be refreshed when new or modified
observations are available. JDemetra+
offers several options for refreshing the output, which are in line with
the [ESS Guidelines on Seasonal Adjustment (2015)](https://ec.europa.eu/eurostat/documents/3859598/6830795/KS-GQ-15-001-EN-N.pdf/d8f1e5f5-251b-4a69-93e3-079031b74bd3) 
requirements.

1.  To refresh the results, open a workspace via the menu *File* → *Open Workspace*. Choose the multi-document option from the
    [*Workspace* window](../reference-manual/workspace.html).
	Double-click on the SAProcessing of your choice to open the
    corresponding window and have its name appear in the menu bar.

	{: .text-center.image-wrapper}

	![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage21.jpg)

	{: .text-center.small}

	**Opening a multi-document**

1.  After clicking on the *SAProcessing* item in the menu bar, slide the
pointer to the *Refresh* option. All the refreshing options unfold.

	{: .text-center.image-wrapper}

	![Text]({{ site.baseurl }}/assets/img/user-guide/UDimage22.jpg)

	{: .text-center.small}

	**The *Refresh* menu**

The meaning of the refreshing options is summed up in the following table.

{: .table .table-style}
| **Option**                                                                              | **Description**                                                                                                                                                                                                                                                                                                               |
|-----------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Current adjustment (AO approach)                                                        | The ARIMA model, outliers and other regression variables are not re-identified, and the values of all associated coefficients are fixed. All new observations are classified as additive outliers and corresponding coefficients are estimated during the regression phase. The transformation type remains unchanged.|
| Partial concurrent adjustment\* → Fixed model                                           | The ARIMA model, outliers and other regression variables are not re-identified and the values of all coefficients are fixed. The transformation type remains unchanged.                                                                                                                                               |
| Partial concurrent adjustment\* → Estimate regression coefficients                      | The ARIMA model, outliers and other regression variables are not re-identified. The coefficients of the ARIMA model are fixed but the regression variables coefficients are re-estimated. The transformation type remains unchanged.                                                                                  |
| Partial concurrent adjustment\* → Estimate regression coefficients + Arima parameters   | The ARIMA model, outliers and other regression variables are not re-identified. All coefficients of the RegARIMA model are re-estimated, for regression variables and ARIMA parameters. The transformation type remains unchanged.                                                                                |
| Partial concurrent adjustment\* → Estimate regression coefficients + Last outliers      | Outliers in the last year of the sample are re-identified. All coefficients of the RegARIMA model, regression variables and Arima parameters, are re-estimated. The transformation type remains unchanged                                                                                                           | 
| Partial concurrent adjustment\* → Estimate regression coefficients + Arima model        | Re-identification of the ARIMA model, outliers and regression variables, except the calendar variables. The transformation type remains unchanged.                                                                                                                                                                            |
| Concurrent                                                                              | Complete re-identification of the whole RegARIMA model, all regression variables and ARIMA model orders.                                                                                                                                                                                                                                                                |


\* According to the *ESS Guidelines on Seasonal Adjustment* (2015), partial
concurrent adjustment is a family of strategies, in which the model,
filters, outliers and calendar regressors are re-identified once a year
and a number of the corresponding coefficients and factors are
re-estimated every time a new or revised data become available.
JDemetra+ offers several types of partial concurrent adjustment: 
- [Estimate fixed model](../case-studies/revision-fixed.html)
- [Estimate regression coefficients](../case-studies/revision-coeff.html)
- [Estimate regression coefficients + Arima parameters](../case-studies/revision-arimaparam.html)
- [Estimate regression coefficients + Last outliers ](../case-studies/revision-last.html)
- [Estimate regression coefficients + Arima model](../case-studies/revision-arimamodel.html)
