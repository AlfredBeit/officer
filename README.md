officer R package
================

<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Build Status](https://travis-ci.org/davidgohel/officer.svg?branch=master)](https://travis-ci.org/davidgohel/officer) [![Coverage Status](https://img.shields.io/codecov/c/github/davidgohel/officer/master.svg)](https://codecov.io/github/davidgohel/officer?branch=master) [![CRAN version](http://www.r-pkg.org/badges/version/officer)](https://cran.r-project.org/package=officer) ![](http://cranlogs.r-pkg.org/badges/grand-total/officer) [![Project Status: WIP - Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)](http://www.repostatus.org/#wip)

![](http://upload.wikimedia.org/wikipedia/commons/f/f7/Artillerie_garde_imperiale.jpg)

officer
-------

The officer package provides lets R users manipulate Word (`.docx`) and PowerPoint (`*.pptx`) documents.

> This package is close to ReporteRs as it produces Word and PowerPoint files but it is faster, do not require `rJava` (but `xml2`) and has less functions that will make it easier to maintain.

A *cursor* concept has been implemented to make it easier the post processing of files. In a Word document, one can use the cursor to reach a particular paragraph containing a given text, or the beginning of the document and the end. In a PowerPoint document, one can set a slide as selected and reach a particular shape (and remove it or add text).

The package [flextable](https://github.com/davidgohel/flextable) brings a full API to produce nice tables and use them with `officer`.

### Installation

You can get the development version from GitHub:

``` r
devtools::install_github("davidgohel/officer")
devtools::install_github("davidgohel/flextable")
```
