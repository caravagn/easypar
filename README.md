
# easypar <a href='https://caravagn.github.io/easypar'><img src='man/figures/logo.png' align="right" height="139" /></a>

<!-- badges: start -->

[![Travis build
status](https://travis-ci.org/caravagn/easypar.svg?branch=master)](https://travis-ci.org/caravagn/easypar)
[![Github All
Releases](https://img.shields.io/github/downloads/caravagn/easypar/total.svg)]()
[![Lifecycle:
maturing](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
<!-- badges: end -->

`easypar` makes it easy to implement parallel computations in R.

#### Rationale

To use this package, you need to have a function that carries out your
desired computation. `easypar` will take care of the burden of turning
that function into a runnable parallel piece of code, offering two
possible soilutions:

  - generating a parallel function call exploiting the `foreach` and
    `doParallel` paradigms for parallel computing.

  - or generating a ready-to-use array job for the popular LSF (Platform
    Load Sharing Facility) workload for distributed high performance
    computing.

With `easypar`, speeding up R computations through parallelism is a
trivial
task.

#### Help and support

[![](https://img.shields.io/badge/GitHub%20Pages-https://caravagn.github.io/easypar/-yellow.svg)](https://caravagn.github.io/easypar)

-----

### Installation

``` r
# install.packages("devtools")
devtools::install_github("caravagn/easypar")
```

-----

#### Copyright and contacts

Giulio Caravagna, PhD. *Institute of Cancer Research, London,
UK*.

[![](https://img.shields.io/badge/Email-gcaravagn@gmail.com-seagreen.svg)](mailto:gcaravagn@gmail.com)
[![](https://img.shields.io/badge/Github-caravagn-seagreen.svg)](https://github.com/caravagn)
[![](https://img.shields.io/badge/Twitter-@gcaravagna-steelblue.svg)](https://twitter.com/gcaravagna)
[![](https://img.shields.io/badge/Personal%20webpage-https://bit.ly/2kc9E6Y-red.svg)](https://sites.google.com/site/giuliocaravagna/)
