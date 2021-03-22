
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ‘exploratory’: an R Package

<!-- badges: start -->

[![R build
status](https://github.com/jinkim3/exploratory/workflows/R-CMD-check/badge.svg)](https://github.com/jinkim3/exploratory/actions)
[![](https://img.shields.io/github/last-commit/jinkim3/exploratory.svg)](https://github.com/jinkim3/exploratory/commits/master)
[![CodeFactor](https://www.codefactor.io/repository/github/jinkim3/exploratory/badge)](https://www.codefactor.io/repository/github/jinkim3/exploratory)
<!-- badges: end -->

### Exploratory Analysis Tool for Behavioral Science Researchers

Conduct numerous exploratory analyses in an instant with a
point-and-click interface (a Shiny App on the local machine). Drag and
drop variables in a data set to categorize them as possible independent,
dependent, moderating, or mediating variables. Then run dozens (or
hundreds) of analyses with one click to uncover any statistically
significant relationships among variables.

This tool also allows conducting simple follow-up analyses (e.g.,
correlation and regression) with the point-and-click interface.

## Warning

Any relationship among variables uncovered using this tool should be
tested in follow-up studies. This tool is designed only to facilitate
exploratory analyses and should NEVER be used for p-hacking (Simmons,
Nelson, & Simonsohn, 2011; Ioannidis 2005).

## Installation

You can install the released version of the package ‘exploratory’ from
[CRAN](https://cran.r-project.org/package=exploratory) with:

``` r
install.packages("exploratory")
```

You can also install the development version from [exploratory on
GitHub](https://github.com/jinkim3/exploratory) with:

``` r
install.packages("devtools")
devtools::install_github("jinkim3/exploratory")
```

If you run into errors while using the package, try updating the package
to the most recent version available on [exploratory on
GitHub](https://github.com/jinkim3/exploratory) with:

``` r
update_exploratory()
```

## Example

Here is an example of using this package.

``` r
library(exploratory)

# update the package 'exploratory'
update_exploratory()

# launch the exploratory analysis tool on a local machine
exploratory(data = mtcars)
```
