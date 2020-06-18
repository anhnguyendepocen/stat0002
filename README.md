
<!-- README.md is generated from README.Rmd. Please edit that file -->

[![Travis-CI Build
Status](https://travis-ci.org/paulnorthrop/stat0002.svg?branch=master)](https://travis-ci.org/paulnorthrop/stat0002)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/paulnorthrop/stat0002?branch=master&svg=true)](https://ci.appveyor.com/project/paulnorthrop/stat0002)

# stat0002 <img src="standalone.png" align="right" />

## Introduction to Probability and Statistics

### What does stat0002 do?

The `stat0002` package provides R code, datasets and vignettes
(tutorials demonstrating how to use R code) to help students taking
STAT0002 Introduction to Probability and Statistics at University
College London (UCL) to understand the course material and to see how R
can be used to perform some of the analyses in the course.

The package is:

  - not complete, but developed enough to be useful to STAT0002
    students;
  - probably of little use to people not taking STAT0002.

### Installation

If you need to install R then you can get it from
[CRAN](https://cran.r-project.org/).

If you would like to use RStudio (a free user-friendly front-end to R)
then you can get it from the [Download RStudio
page](https://www.rstudio.com/products/rstudio/download/). Find **All
Installers** near the bottom of the page and choose the installer that
is appropriate for your operating system.

To install the `stat0002` package from GitHub type the following at the
R Console command prompt `>`.

``` r
install.packages("remotes")

install.packages(c("plotrix", "rpanel", "rust", "smovie", "tkrplot", "MASS", "knitr", "distributions3"), 
                 dependencies = "Depends")
```

You only need to do this (install the `remotes` package etc) once. Then
install `stat0002` (or reinstall it to get the latest version) using

``` r
remotes::install_github("paulnorthrop/stat0002", dependencies = "Depends", build_vignettes = TRUE)
```

### Getting started

Then type

``` r
library(stat0002)
?stat0002
```

to open the main help page, which contains links to vignettes, datasets
and other sources of information. If `?stat0002` doesn’t work then close
RStudio, reopen it and try again.

You will find that some vignettes contain ideas that we have not yet
covered in lectures. If you want to try to understand these ideas before
we cover them then please use the links to further information that have
been provided.

If you have any questions about this package please ask them via the
[STAT0002 Moodle Discussion
Forum](https://moodle.ucl.ac.uk/mod/hsuforum/view.php?id=866683).
