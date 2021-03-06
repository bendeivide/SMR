
[![CRAN
status](https://www.r-pkg.org/badges/version/midrangeMCP)](https://CRAN.R-project.org/package=SMR)
[![](https://cranlogs.r-pkg.org/badges/SMR?color=orange)](https://cran.r-project.org/package=SMR)
[![Last-changedate](https://img.shields.io/badge/last%20change-2022--05--04-yellowgreen.svg)](https://github.com/bendeivide/SMR/commit/master)
[![codecov](https://codecov.io/gh/bendeivide/SMR/branch/master/graph/badge.svg)](https://codecov.io/gh/bendeivide/SMR)
<!-- [![Build Status](https://travis-ci.com/bendeivide/SMR.svg?branch=master)](https://travis-ci.com/bendeivide/SMR) -->
[![Lifecycle:
stable](https://img.shields.io/badge/lifecycle-maturing-brightgreen.svg)](https://www.tidyverse.org/lifecycle/#maturing)

# <i class="fas fa-box-open" aria-hidden="true"></i> SMR <img src='man/figures/logo.png' align="right" width="139" style="float:right; width:139px;"/>

[SMR](https://bendeivide.github.io/midrangeMCP/) is an R packago aim to
compute studentized normal midrange distribution. [In 2017, this
distribution was published in the Revista Ciência e
Agrotecnologia](http://repositorio.ufla.br/bitstream/1/29962/1/ARTIGO_Externally%20studentized%20normal%20midrange%20distribution.pdf).
This work was developed during the master in Statistics and Agricultural
Experimentation, by the [Federal University of Lavras](https://ufla.br/)
(UFLA/BRAZIL). The authors of this work are Professor [Daniel Furtado
Ferreira](http://www.dex.ufla.br/~danielff/) and [Ben Dêivide de
Oliveira Batista](http://bendeivide.github.io), Professor of Statistics
at the [Federal University of São João del-Rei](https://ufsj.edu.br/)
(UFSJ/BRAZIL). Today, we have the collaboration of a student of
scientific initiation, [Diego Arthur Bispo Justino de
Oliveira](https://digoarthur.github.io/), student of Mechatronics
Engineering at UFSJ and [Matheus Fernando Rodrigues Santos](), student
of Mechatronics Engineering at UFSJ. [The package was published in 2014
in R
journal](https://journal.r-project.org/archive/2014/RJ-2014-029/index.html)

## <i class="fa fa-download" aria-hidden="true"></i> Instalation

To install the [SMR](https://CRAN.R-project.org/package=SMR) package via
CRAN:

``` r
install.packages("SMR")
```

To install via GitHub:

``` r
install.packages("devtools")
install_github("bendeivide/SMR")
```

## <i class="fa fa-code" aria-hidden="true"></i> Functions

The package follows the same structure as the probability functions
implemented in R. That is: the probability density function (`dSMR`),
the cumulative distribution function (`pSMR`), the quantile function
(`qSMR`) and the random number generating function (`rSMR`). The
pseudocodes and illustrative examples of how to use the package are
presented.

## <i class="fa fa-pencil-alt" aria-hidden="true"></i> Citation

To cite this work use:

``` latex
@article{RJ-2014-029,
  author = {Ben Dêivide Oliveira Batista and Daniel Furtado Ferreira},
  title = {{SMR: An R package for computing the externally studentized
          normal midrange distribution}},
  year = {2014},
  journal = {{The R Journal}},
  doi = {10.32614/RJ-2014-029},
  url = {https://doi.org/10.32614/RJ-2014-029},
  pages = {123--136},
  volume = {6},
  number = {2}
}
```

## <i class="fa fa-globe" aria-hidden="true"></i> Website

For a complete description of the `SMR` package, **visit our website at
[bendeivide.github.io/SMR/](https://bendeivide.github.io/SMR/)**

## <i class="fas fa-newspaper" aria-hidden="true"></i> News

-   Version 2.0.2 (Under development):

-   Version 2.0.0 (2014-10-16):

-   Version 2.0.0 (2014-10-16):

-   Version 1.0.0 (2012-10-19): Functions implemented: `dSMR`, `pSMR`,
    `qSMR` and `rSMR`.
