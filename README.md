Can we
================
Your names in alphabetical order with Dan
5/29/2020

# How do sentiment models work?

Lexicons thats how, here are 5 randomly sampled words from four popular
lexicons and then ours. Here is where we can add a whole bunch of text.
I will :brain: use a bunch of the options to really help you see how
well this works. \[1\]

  - amazing
      - boop

## Wow

### Smaller

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

| reference |     balance |       yar |
| --------: | ----------: | --------: |
|         1 |   1.5865385 | 1.7997380 |
|         2 |   1.9202899 | 0.8152237 |
|         3 | \-0.3229167 | 2.3664618 |

A subset of our system.

    ## # A tibble: 5 x 3
    ##   word        value type 
    ##   <chr>       <dbl> <chr>
    ## 1 perpetrator    -2 Afinn
    ## 2 convinces       1 Afinn
    ## 3 agonise        -3 Afinn
    ## 4 vulnerable     -2 Afinn
    ## 5 swift           2 Afinn

    ## # A tibble: 5 x 3
    ##   word         sentiment type 
    ##   <chr>        <chr>     <chr>
    ## 1 ministry     trust     NRC  
    ## 2 morbid       negative  NRC  
    ## 3 presumptuous anger     NRC  
    ## 4 wrinkled     sadness   NRC  
    ## 5 synonymous   negative  NRC

    ## # A tibble: 5 x 3
    ##   word           sentiment type 
    ##   <chr>          <chr>     <chr>
    ## 1 traitorously   negative  Bing 
    ## 2 blundering     negative  Bing 
    ## 3 licentiousness negative  Bing 
    ## 4 discoutinous   negative  Bing 
    ## 5 raptureous     positive  Bing

    ## # A tibble: 5 x 3
    ##   word         sentiment    type    
    ##   <chr>        <chr>        <chr>   
    ## 1 annulment    negative     Loughran
    ## 2 convicting   litigious    Loughran
    ## 3 assuming     uncertainty  Loughran
    ## 4 dictates     constraining Loughran
    ## 5 notarization litigious    Loughran

    ## # A tibble: 5 x 5
    ##   word       president score occassion              type  
    ##   <chr>      <chr>     <dbl> <chr>                  <chr> 
    ## 1 our        obama         1 Selma                  pressy
    ## 2 liberty    obama         2 Usama Bin Laden (2011) pressy
    ## 3 prosperity obama         4 Usama Bin Laden (2011) pressy
    ## 4 least      obama         1 Trayvon Martin (2013)  pressy
    ## 5 making     obama         1 SOTU_15                pressy

| word        | value | type  |
| :---------- | ----: | :---- |
| perpetrator |   \-2 | Afinn |
| convinces   |     1 | Afinn |
| agonise     |   \-3 | Afinn |

A subset of our system.

| word         | sentiment |
| :----------- | :-------- |
| ministry     | trust     |
| morbid       | negative  |
| presumptuous | anger     |
| wrinkled     | sadness   |
| synonymous   | negative  |

A subset of our system.

## Including Plots

Here is the big plot that loos super
messy.

![](README_files/figure-gfm/pressure-1.png)<!-- -->![](https://i.kym-cdn.com/photos/images/newsfeed/000/598/653/75f.jpg)<!-- -->

And it is clear that this is a graphic that says some
stuff.

    ## Warning: Removed 5 rows containing missing values (geom_point).

![](README_files/figure-gfm/description%20of%20what%20is%20up-1.png)<!-- -->

``` marginfigure
Here is a random side note. As you may know, I love this stuff. 
```

Values of under zero indicate that our analysis was substantially more
positive than Afinn

1.  [Obama’s
    Farewell](https://www.presidency.ucsb.edu/documents/farewell-address-the-nation-from-chicago-illinois)
