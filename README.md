
# pets

Provides two example [tibbles](https://tibble.tidyverse.org), `pets` and
`owners`.

``` r
library(pets)
pets
```

    ## # A tibble: 5 x 2
    ##   pet     species 
    ##   <chr>   <chr>   
    ## 1 Fifi    Dog     
    ## 2 Goldi   Goldfish
    ## 3 Mittens Cat     
    ## 4 Rex     Dog     
    ## 5 Snowy   Dog

``` r
owners
```

    ## # A tibble: 5 x 2
    ##   owner pet    
    ##   <chr> <chr>  
    ## 1 Alice Snowy  
    ## 2 Bob   Mittens
    ## 3 Carol Mittens
    ## 4 Dan   Goldi  
    ## 5 Erin  Pancho
