# bis620.2022
---
output: github_document
---

<!-- README.md is generated from README.Rmd. Please edit that file -->

```{r, include = FALSE}
knitr::opts_chunk$set(
  collapse = TRUE,
  comment = "#>",
  fig.path = "man/figures/README-",
  out.width = "100%"
)
```

# bis620.2022

<!-- badges: start -->
  [![test-coverage](https://github.com/XinyiOlivia/bis620.2022/actions/workflows/test-coverage.yaml/badge.svg?branch=main)](https://github.com/XinyiOlivia/bis620.2022/actions/workflows/test-coverage.yaml)
[![lint](https://github.com/XinyiOlivia/bis620.2022/actions/workflows/lint.yaml/badge.svg)](https://github.com/XinyiOlivia/bis620.2022/actions/workflows/lint.yaml)
[![R-CMD-check](https://github.com/Juli66/bis620.2022/actions/workflows/R-CMD-check.yaml/badge.svg?branch=main)](https://github.com/XinyiOlivia/bis620.2022/actions/workflows/R-CMD-check.yaml)
[[![codecov](https://codecov.io/gh/XinyiOlivia/bis620.2022/branch/main/graph/badge.svg?token=K0SC6W7K23)](https://codecov.io/gh/XinyiOlivia/bis620.2022))
<!-- badges: end -->
  
The motivation of bis620.2022 visualization of a time series dataset with a spectral function

## Test Coverage

url:
  "https://app.codecov.io/gh/XinyiOlivia/bis620.2022"

## Installation

You can install the development version of bis620.2022 from [GitHub](https://github.com/) with: <br>
`install.packages("devtools")` <br>
`devtools::install_github("XinyiOlivia/bis620.2022")`

## Example

```{r example}
devtools::install_github("XinyiOlivia/bis620.2022")
library(bis620.2022)
data(ukb_accel)
ukb_accel[1:100, ] |>
  accel_plot()
```
