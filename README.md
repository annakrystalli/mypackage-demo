
<!-- README.md is generated from README.Rmd. Please edit that file -->

# mypackage

<!-- badges: start -->

[![R-CMD-check](https://github.com/annakrystalli/mypackage-demo/workflows/R-CMD-check/badge.svg)](https://github.com/annakrystalli/mypackage-demo/actions)
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
#> 
#>  ----- 
#> Hello world from Anna! 
#>  ------ 
#>     \   
#>      \  
#>       \
#>        ,
#>     _,,)\.~,,._
#>      (()`  ``)\))),,_
#>       |     \ ''((\)))),,_          ____
#>       |6`   |   ''((\())) "-.____.-"    `-.-,
#>       |    .'\    ''))))'                  \)))
#>       |   |   `.     ''                     ((((
#>       \, _)     \/                          |))))
#>        `'        |                          (((((
#>                  \                  |       ))))))
#>                   `|    |           ,\     /((((((
#>                    |   / `-.______.<  \   |  )))))
#>                    |   |  /         `. \  \  ((((
#>                    |  / \ |           `.\  | (((
#>                    \  | | |             )| |  ))
#>                     | | | |             || |  '   [endless.horse]
#>                     | | | |             || |
```

This is a basic example which shows you how to print a personalised
greeting:

````` r
hello("Lucy Elen")
#> 
#>  -------------- 
#> Hello Lucy Elen from Anna! 
#>  --------------
#>     \
#>       \
#>         \
#>                    _.-````'-,_
#>          _,.,_ ,-'`           `'-.,_
#>        /)     (                   '``-.
#>       ((      ) )                      `\
#>         \)    (_/                        )\
#>         |       /)           '    ,'    / \
#>         `\    ^'            '     (    /  ))
#>           |      _/\ ,     /    ,,`\   (  "`
#>           \Y,   |   \  \  | ````| / \_ \
#>             `)_/      \  \  )    ( >  ( >
#>                        \( \(     |/   |/
#>           mic & dwb  /_(/_(    /_(  /_(
#> 
`````
