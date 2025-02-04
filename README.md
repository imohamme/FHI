
<!-- README.md is generated from README.Rmd. Please edit that file -->

# FHI

<!-- badges: start -->
<!-- badges: end -->

FHI - Calculates a range of Freshwater Health Index metrics.

# Documentation

The Freshwater Health Index (FHI) offers a framework for water managers
and decision-makers to analyze the health of their basins, understand
the trade-offs and consequences of their actions, and discuss approaches
to creating healthy, sustainable watersheds into the future. FHI Users
are encouraged to visit [FHI’s
documentation](https://www.conservation.org/projects/freshwater-health-index)
to learn more on FHI functionalities and capabilities.

## Installation

You can install the development version of FHI like so:

``` r
library(devtools)
install_github("Nick-Souter/FHI", build_vignettes = TRUE)
library(FHI)
```

## Example

This is a basic example which shows you how to calculate deviation from
natural flow (DvNF) for modeled flow/gauge height data:

``` r
library(FHI)

DvNF_model()
```

# Contributors

-   **Nicholas J Souter** - *Initial work* -
    [Nick-Souter](https://github.com/Nick-Souter/FHI)
-   **Ibrahim Mohammed** - *Initial & Finishing work* -
    [![imohamme](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-6542-319X)
