Can we
================
Your names in alphabetical order with Dan
5/29/2020

# How do sentiment models work?

Lexicons thats how, here are 5 randomly sampled words from four popular
lexicons and then ours. Here is where we can add a whole bunch of text.
I will use a bunch of the options to really help you see how well this
works. \[1\]

## Wow

### Smaller

\*List +item 1 +item 2

| Column 1 | Column 2       | Column 3 |
| -------- | -------------- | -------- |
| Obama    | President      | Dude     |
| Bush     | President      | Bro      |
| Biden    | Vice President | Guy      |

\#\#A variety of things

| word      | president | score | occassion |
| :-------- | :-------- | ----: | :-------- |
| economy   | obama     |     3 | SOTU      |
| polan     | obama     |     2 | SOTU      |
| health    | obama     |     2 | SOTU      |
| education | obama     |     2 | SOTU      |

A subset of our system.

    ## # A tibble: 5 x 3
    ##   word           value type 
    ##   <chr>          <dbl> <chr>
    ## 1 tumor             -2 Afinn
    ## 2 misleading        -3 Afinn
    ## 3 son-of-a-bitch    -5 Afinn
    ## 4 willingness        2 Afinn
    ## 5 favorites          2 Afinn

    ## # A tibble: 5 x 3
    ##   word      sentiment    type 
    ##   <chr>     <chr>        <chr>
    ## 1 twinkle   anticipation NRC  
    ## 2 deserve   positive     NRC  
    ## 3 tax       sadness      NRC  
    ## 4 aggressor negative     NRC  
    ## 5 arid      sadness      NRC

    ## # A tibble: 5 x 3
    ##   word           sentiment type 
    ##   <chr>          <chr>     <chr>
    ## 1 proactive      positive  Bing 
    ## 2 precipitous    negative  Bing 
    ## 3 disingenuously negative  Bing 
    ## 4 worthlessly    negative  Bing 
    ## 5 failed         negative  Bing

    ## # A tibble: 5 x 3
    ##   word           sentiment    type    
    ##   <chr>          <chr>        <chr>   
    ## 1 honor          positive     Loughran
    ## 2 frustrate      negative     Loughran
    ## 3 mandates       constraining Loughran
    ## 4 undeterminable uncertainty  Loughran
    ## 5 nonperformance negative     Loughran

    ## # A tibble: 5 x 5
    ##   word     president score occassion                        type  
    ##   <chr>    <chr>     <dbl> <chr>                            <chr> 
    ## 1 nation's obama         2 Selma                            pressy
    ## 2 were     obama        -1 SOTU_15                          pressy
    ## 3 protect  obama         3 SOTU_15                          pressy
    ## 4 tragedy  obama        -5 Arizona Shooting Memorial (2011) pressy
    ## 5 sooting  obama        -5 Arizona Shooting Memorial (2011) pressy

| word           | value | type  |
| :------------- | ----: | :---- |
| tumor          |   \-2 | Afinn |
| misleading     |   \-3 | Afinn |
| son-of-a-bitch |   \-5 | Afinn |

A subset of our system.

| word    | sentiment    |
| :------ | :----------- |
| twinkle | anticipation |
| deserve | positive     |

A subset of our system.

## Including Plots

Here is the big plot that loos super
messy.

![](README_files/figure-gfm/pressure-1.png)<!-- -->![](README_files/figure-gfm/pressure-2.png)<!-- -->

And it is clear that this is a graphic that says some
stuff.

    ## Warning: Removed 5 rows containing missing values (geom_point).

![](README_files/figure-gfm/description%20of%20what%20is%20up-1.png)<!-- -->

``` marginfigure
Here is a random side note. As you may know, I love this stuff. 
```

Values of under zero indicate that our analysis was substantially more
positive than Afinn

1.  Noop norp zorp
