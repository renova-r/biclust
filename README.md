# biclust

Biclustering algorithms (Cheng and Church, spectral, plaid, xMotifs, Bimax and others) with preprocessing, visualisation and validation tools.

Compatibility updates by Renova.

Version 2.0.3.1.9001 makes `class()` checks safe for objects with more than one class (`class(x)[1L]`, and `inherits()` for `try-error`), changes two Rd links to the `additivityTests` package into `\pkg{}` markup, and reformats two lines of `NEWS`.

## Install

```r
install.packages("biclust", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/biclust@renova-2.0.3.1.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

biclust is by Sebastian Kaiser (maintainer), Rodrigo Santamaria, Tatsiana Khamiakova, Martin Sill, Roberto Theron, Luis Quintales, Friedrich Leisch, Ewoud De Troyer and Sami Leon; the original CRAN package is at <https://CRAN.R-project.org/package=biclust>. License: GPL-3 as declared in DESCRIPTION; see [COPYING.GPL-3](COPYING.GPL-3) (the original [COPYING](COPYING) file contains the GPL version 2 text).
