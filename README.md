
<!-- README.md is generated from README.Rmd. Please edit that file -->

# newr

<!-- badges: start -->
<!-- badges: end -->

The goal of newr is to practise making packages.

## Installation

You can install the development version of newr from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("tphil99/newr")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(newr)
```

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

`devtools::build_readme()`

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
