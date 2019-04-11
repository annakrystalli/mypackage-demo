
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->

<!-- badges: end -->

The goal of mypackage is to print a personalised greeting from me\!

## Installation

You can install the development version of mypackage from GitHub with:

``` r
devtools::install_github("annakrystalli/mypackage")
```

## Example

This is a basic example which shows you how to print a generic greeting:

``` r
library(mypackage)
hello()
#> Colors cannot be applied in this environment :( Try using a terminal or RStudio.
#> 
#>  ----- 
#> Hello world from Anna! 
#>  ------ 
#>     \   
#>      \  
#>       \
#>        \
#> 
#>         >o  .
#>          ===    [ab]
#> 
```

This is a basic example which shows you how to print a personalised
greeting:

``` r
hello("Lucy Elen")
#> Colors cannot be applied in this environment :( Try using a terminal or RStudio.
#> 
#> 
#>  ----- 
#> Hello Lucy Elen from Anna! 
#>  ------ 
#>     \   
#>      \
#>      (   )
#>   (   ) (
#>    ) _   )
#>     ( \_
#>   _(_\ \)__
#>  (____\ ___)) [nosig]
```
