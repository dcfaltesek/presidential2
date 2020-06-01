Can we
================
Your names in alphabetical order with Dan
5/29/2020

# How do sentiment models work?

Lexicons thats how, here are 5 randomly sampled words from four popular
lexicons and then ours. Here is where we can add a whole bunch of text.
I will use a bunch of the options to really help you see how well this
works.

## Wow

### Smaller

\*List +item 1 +item 2

| Column 1 | Column 2       | Column 3 |
| -------- | -------------- | -------- |
| Obama    | President      | Dude     |
| Bush     | President      | Bro      |
| Biden    | Vice President | Guy      |

    ## # A tibble: 5 x 3
    ##   word     value type 
    ##   <chr>    <dbl> <chr>
    ## 1 lively       2 Afinn
    ## 2 defeated    -2 Afinn
    ## 3 exploit     -2 Afinn
    ## 4 dislike     -2 Afinn
    ## 5 obstacle    -2 Afinn

    ## # A tibble: 5 x 3
    ##   word         sentiment type 
    ##   <chr>        <chr>     <chr>
    ## 1 wildfire     fear      NRC  
    ## 2 perpetuation negative  NRC  
    ## 3 outcry       surprise  NRC  
    ## 4 intelligent  trust     NRC  
    ## 5 coalesce     trust     NRC

    ## # A tibble: 5 x 3
    ##   word        sentiment type 
    ##   <chr>       <chr>     <chr>
    ## 1 defective   negative  Bing 
    ## 2 intrude     negative  Bing 
    ## 3 unauthentic negative  Bing 
    ## 4 hostility   negative  Bing 
    ## 5 obstacle    negative  Bing

    ## # A tibble: 5 x 3
    ##   word        sentiment type    
    ##   <chr>       <chr>     <chr>   
    ## 1 invalidity  negative  Loughran
    ## 2 annulment   negative  Loughran
    ## 3 tragedy     negative  Loughran
    ## 4 rescinded   litigious Loughran
    ## 5 negligently negative  Loughran

    ## # A tibble: 5 x 5
    ##   word        president score occassion                        type  
    ##   <chr>       <chr>     <dbl> <chr>                            <chr> 
    ## 1 died        obama        -2 Arizona Shooting Memorial (2011) pressy
    ## 2 doubling    obama         2 State of the Union (2011)        pressy
    ## 3 electricity obama         2 Climate Change (2013)            pressy
    ## 4 friends     obama         1 Arizona Shooting Memorial (2011) pressy
    ## 5 same        obama        -1 Selma                            pressy

## Including Plots

Here is the big plot that loos super
messy.

![](README_files/figure-gfm/pressure-1.png)<!-- -->![](README_files/figure-gfm/pressure-2.png)<!-- -->

And it is clear that this is a graphic that says some
stuff.

    ## Warning: Removed 5 rows containing missing values (geom_point).

![](README_files/figure-gfm/description%20of%20what%20is%20up-1.png)<!-- -->

Values of under zero indicate that our analysis was substantially more
positive than Afinn
