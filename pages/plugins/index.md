---
layout: left-menu
title: Plugins
tagline: technical documentation for JDemetra+ using GitHub Pages
description: Basics
order: 0
---
<br/>
A plugin is a software component that can extend JDemetra+ functionalities. 
Plugins can be shared between the users and installed individually. The installation procedure is decribed in the [dedicated item](../reference-manual/tools.html#plugins) of the Reference Manual section.

The list below presents the plugins <a href="https://bbkrd.github.io/" target="_blank">developed by the Bundesbank</a> and the National Bank of Belgium..
#### **Concur**<br>
The plug-in ConCur supports the controlled current adjustment approach. It supports the storage of the current components and offers graphical tools to compare forecasted and re-estimated figures. Furthermore, a pre-defined summary of the output containing the most important quality measures can be exported to HTML files.
#### **KIX**<br>
The plug-in KIX (German for chain-linked index) has been designed to facilitate the handling of this index type. It offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth.
#### **KIX 2.0**<br>
KIX 2.0 offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth following the concept of annual overlap. Contributions to growth are calculated with the partial contribution to growth approach.
#### **KIX_E**<br>
KIX_E offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth following the concept of one-period overlap. Contributions to growth are calculated with the aid of the Ribe (1999) contribution to growth approach.
#### **KIX-CC**<br>
The program KIX-CC offers for continuously chain-linked indices the aggregation or disaggregation of two or more indices, or the calculation of contributions to growth.
#### **SpecParser**<br>
The plug-in SpecParser is designed to migrate already existing specification files (X-12-ARIMA compatible .spc- and .mta-(meta)-files) to JD+. The plugin automatically translates all relevant information (e.g. time series data, regression variables, specifications) from the X-12-ARIMA spc-files and constructs an analogous seasonal adjustment document in JD+.
#### **TransReg**<br>	
The plug-in TransReg allows the user to carry out grouping and centring of user-defined regression variables in JD+.
	
=======
The list below presents the plugins developed by the Bundesbank and the National Bank of Belgium.

### Bundesbank plug-ins

<table class="table table-bordered">
  <tr>
    <th colspan="2">Plug-in</th>
    <th>Short Description</th>
  </tr>
  <tr>
    <td colspan="2"><a href="https://immurb.github.io/pages/concur/">ConCur</a></td>
    <td>The plug-in ConCur supports the controlled current adjustment approach. It supports the storage of the current components and offers graphical tools to compare forecasted and re-estimated figures. Furthermore, a pre-defined summary of the output containing the most important quality measures can be exported to HTML files.</td>
  </tr>
  <tr>
    <td style = "border-right: 0px" rowspan="4"><a href="https://immurb.github.io/pages/kix/">KIX</a></td>
    <td style = "border-left: 0px"></td>
    <td>The plug-in KIX (German for chain-linked index) has been designed to facilitate the handling of this index type. It offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth.</td>
  </tr>
  <tr>
    <td><a href="https://immurb.github.io/pages/kix/kix2/">KIX2.0</a></td>
    <td>KIX 2.0 offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth following the concept of annual overlap. Contributions to growth are calculated with the partial contribution to growth approach.</td>
  </tr>
  <tr>
    <td><a href="https://immurb.github.io/pages/kix/kixe/">KIXE</a></td>
    <td>KIX_E offers addition and subtraction of two or more chain-linked time series as well as the computation of contributions of growth following the concept of one-period overlap. Contributions to growth are calculated with the aid of the Ribe (1999) contribution to growth approach.</td>
  </tr>
  <tr>
    <td><a href="https://immurb.github.io/pages/kix/kixcc/">KIX&#8209;CC</a></td>
    <td>The program KIX-CC offers for continuously chain-linked indices the aggregation or disaggregation of two or more indices, or the calculation of contributions to growth.</td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://immurb.github.io/pages/specparser/">SpecParser</a></td>
    <td>The plug-in SpecParser is designed to migrate already existing specification files (X-12-ARIMA compatible .spc- and .mta-(meta)-files) to JD+. The plugin automatically translates all relevant information (e.g. time series data, regression variables, specifications) from the X-12-ARIMA spc-files and constructs an analogous seasonal adjustment document in JD+.</td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://immurb.github.io/pages/transreg/">TransReg</a></td>
    <td>The plug-in TransReg allows the user to carry out grouping and centring of user-defined regression variables in JD+.</td>
  </tr>
</table>

### National Bank of Belgium plug-ins

<table class="table table-bordered">
  <tr>
    <th colspan="2">Plug-in</th>
    <th>Short Description</th>
  </tr>
  <tr>
    <td colspan="2"><a href="https://github.com/nbbrd/jdemetra-access">Access</a></td>
    <td>This JDemetra+ extension is a pure java library for reading time series from <a href="https://en.wikipedia.org/wiki/Microsoft_Access">MS Access databases</a>.<br/>It currently supports versions 2000-2016 read/write and 97 read-only.<br/>Being a pure Java library, you don't need MS Access installed in order to read Access files.</td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://github.com/nbbrd/jdemetra-dotstat">SDMX</a></td>
    <td>This plugin provides time series from <a href="https://sdmx.org/">SDMX</a> to JDemetra+ by querying <a href="https://github.com/nbbrd/jdemetra-dotstat/wiki/Supported-web-services">web services</a> or parsing <a href="https://github.com/nbbrd/jdemetra-dotstat/wiki/Supported-file-formats">files</a>.</td>
  </tr>
  <tr>
    <td style = "border-right: 0px" rowspan="6"><a href="https://github.com/nbbrd/jdemetra-sa-advanced">SA&nbsp;Advanced</a></td>
    <td style = "border-left: 0px"></td>
    <td>This module provides some experimental seasonal adjustment methods (with RegArima preprocessing):<br/>basic structural models, generalized airline models and airline + seasonal noise models (called mixed airline)</td>
  </tr>
  <tr>
    <td>gairline</td>
    <td>Generalized airline model</td>
  </tr>
  <tr>
    <td>mairline</td>
    <td>Mixed airline model</td>
  </tr>
  <tr>
    <td>mixedfreq</td>
    <td>Mixed frequencies seasonal adjustment</td>
  </tr>
  <tr>
    <td>sssts</td>
    <td>Seasonal specific structural time series</td>
  </tr>
  <tr>
    <td>sts</td>
    <td>Structural time series</td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://github.com/nbbrd/jdemetra-benchmarking">Benchmarking</a></td>
    <td>This module provides some experimental methods for temporal disaggregation and multi-variate benchmarking:<br/>Chow-Lin, Fernandez, Litterman, Cholette, Calendarization...</td>
  </tr>
  <tr>
    <td colspan="2"><a href="https://github.com/nbbrd/jdemetra-nowcasting">Nowcasting</a></td>
    <td>Nowcasting is often defined as the prediction of the present, the very near future and the very recent past. The plug-in developed at the National Bank of Belgium helps to operationalize the process of nowcasting. It can be used to specify and estimate dynamic factor models and visualize how the real-time dataflow updates expectations, as for instance in Banbura and Modugno (2010). The software can also be used to perform pseudo out-of-sample forecasting evaluations that consider the calendar of data releases, contributing to the formalization of the nowcasting problem originally proposed by Giannone, et al. (2008) or Evans (2005).</td>
  </tr>
</table>
