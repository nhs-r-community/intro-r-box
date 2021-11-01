
<!-- README.md is generated from README.Rmd. Please edit that file -->

# NHSRtraining

<!-- badges: start -->
<!-- badges: end -->

## Goal

The goal of `NHSRtraining` is to supplement the NHSR [Introduction to R
and R Studio training](https://nhs-r-community.github.io/intro_r/) and
the [GitHub repository](https://github.com/nhs-r-community/intro_r) with
exercises that can be completed as part of the course or

## Installation

You can install the development version of NHSRtraining from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("nhs-r-community/NHSRtraining")
```

## Running the tutorials

Unlike with usual packages where `library(NHSRtraining)` would be used,
this package uses `learnr` so, once the package is installed, the
following code details what is available:

``` r
learnr::available_tutorials("NHSRtraining")
```

and running each tutorial:

``` r
learnr::run_tutorial("list-tutorial-name", package = "NHSRtraining")
```

## Thanks and credits

This package has been greatly inspired in its structure from other “box”
training like [Penguins in a
box](https://github.com/demar01/penguinsbox) (in both English and
Spanish) and [Data Science in a Box](https://datasciencebox.org/).

Materials used to build the package are from the Forwards workshop:
[Packages in a
nutshell](https://github.com/forwards/workshops/tree/dc5b9fba5cdfbebc737a0a393b374a18378be122).

## Comments or Issues

If you have any comments or notice any errors, please create an
[issue](https://github.com/nhs-r-community/NHSRtraining/issues).
