Overview
================
GameLab Team
5/29/2020

## How do sentiment models work?

Lexicons thats how, here are 5 randomly sampled words from four popular
lexicons and then ours

    ## # A tibble: 5 x 3
    ##   word          value type 
    ##   <chr>         <dbl> <chr>
    ## 1 green washing    -3 Afinn
    ## 2 benefitted        2 Afinn
    ## 3 penalty          -2 Afinn
    ## 4 treason          -3 Afinn
    ## 5 poorer           -2 Afinn

    ## # A tibble: 5 x 3
    ##   word        sentiment type 
    ##   <chr>       <chr>     <chr>
    ## 1 steal       sadness   NRC  
    ## 2 marvelous   joy       NRC  
    ## 3 yelp        fear      NRC  
    ## 4 hygienic    positive  NRC  
    ## 5 shoplifting negative  NRC

    ## # A tibble: 5 x 3
    ##   word          sentiment type 
    ##   <chr>         <chr>     <chr>
    ## 1 broken        negative  Bing 
    ## 2 invulnerable  positive  Bing 
    ## 3 lorn          negative  Bing 
    ## 4 unreliability negative  Bing 
    ## 5 bogus         negative  Bing

    ## # A tibble: 5 x 3
    ##   word          sentiment    type    
    ##   <chr>         <chr>        <chr>   
    ## 1 seems         uncertainty  Loughran
    ## 2 hazard        negative     Loughran
    ## 3 hereunto      litigious    Loughran
    ## 4 pretrial      negative     Loughran
    ## 5 noncancelable constraining Loughran

    ## # A tibble: 5 x 5
    ##   word     president score occassion                 type  
    ##   <chr>    <chr>     <dbl> <chr>                     <chr> 
    ## 1 fastest  obama         2 SOTU_15                   pressy
    ## 2 health   obama         2 State of the Union (2011) pressy
    ## 3 honor    obama         3 Selma                     pressy
    ## 4 al qaida obama        -5 Usama Bin Laden (2011)    pressy
    ## 5 school   obama         2 SOTU_15                   pressy

## Including Plots

You can also embed plots, for example:

![](README_files/figure-gfm/pressure-1.png)<!-- -->

And it is clear that this is a graphic that says some
stuff.

    ## Warning: Removed 5 rows containing missing values (geom_point).

![](README_files/figure-gfm/description%20of%20what%20is%20up-1.png)<!-- -->

Values of under zero indicate that our analysis was substantially more
positive than Afinn
