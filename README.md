
<!-- README.md is generated from README.Rmd. Please edit that file -->

# epgdata

<!-- badges: start -->
<!-- badges: end -->

`epgdata` is an R data package that is supplementary to the `EPGminer`
package and needed for the demo vignette. The demo data is included here
as a separate package due to the inherent size of EPG data sets. Please
refer to the `EPGminer` package itself
[here](https://github.com/LylChun/EPGminer) for more discussion of EPG
data and analysis.

## Installation

You can install the `epgdata` package from github as follows.

``` r
if (!require(devtools)){
  install.packages("devtools")
}
devtools::install_github("LylChun/epgdata")
```

## Raw EPG data

The `epgdata` package contains 12 hours of raw EPG voltage data from an
example dataset (.txt) along with it’s accompanying manual annotation
file (.ANA) To see how one may analyze this data, please see the
`EPGminer` package [here](https://github.com/LylChun/EPGminer)
