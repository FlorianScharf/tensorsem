<p align="center">
  <img src="img/tensorsem.png" width="300px"></img>
  <br/>
  <span>
    <a href="https://CRAN.R-project.org/package=tensorsem"><img src="http://www.r-pkg.org/badges/version/tensorsem"></img></a>
    <a href="https://travis-ci.org/vankesteren/tensorsem"><img src="https://travis-ci.org/vankesteren/tensorsem.svg?branch=master"></img></a>
  </span>
  <h5 align="center">Structural Equation Modeling using TensorFlow</h5>
</p>
<br/>

## Description
An `R` package for structural equation modeling using TensorFlow. This is a stable branch.

## Installation
```r
# First, install TensorFlow version 1.13.1 for R
# Newer versions _may_ work but are untested.
remotes::install_github("rstudio/tensorflow")
tensorflow::install_tensorflow(version = "1.13.1")

# Then, install tensorsem from this branch
remotes::install_github("vankesteren/tensorsem")

# Lastly, load and run the example
library(tensorsem)
example(tf_sem)
```
