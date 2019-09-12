# ABMI R Package Repository

https://abbiodiversity.github.io/drat/

## Setup

Install the {drat} R package and add the ABbiodiversity CRAN-like repository:

``` R
install.packages("drat")
drat::addRepo("ABbiodiversity")
```

Now you can use `install.packages()` to install R packages from the repository
without the need to use {devtools::install_github} or {remotes::install_github}.
