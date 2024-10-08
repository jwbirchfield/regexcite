
# regexcite

The goal of regexcite is to facilitate splitting a character string into
a character vector.

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("jwbirchfield/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
x <- c('a,b,c')
regexcite::strsplit1(x = x, split = ',')
#> [1] "a" "b" "c"
```
