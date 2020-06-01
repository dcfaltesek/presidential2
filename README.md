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
    ##   word        value type 
    ##   <chr>       <dbl> <chr>
    ## 1 commitment      2 Afinn
    ## 2 hiding         -1 Afinn
    ## 3 restricting    -2 Afinn
    ## 4 sarcastic      -2 Afinn
    ## 5 imposes        -1 Afinn

    ## # A tibble: 5 x 3
    ##   word       sentiment    type 
    ##   <chr>      <chr>        <chr>
    ## 1 complexity negative     NRC  
    ## 2 offset     anticipation NRC  
    ## 3 evict      sadness      NRC  
    ## 4 parasite   fear         NRC  
    ## 5 marry      surprise     NRC

    ## # A tibble: 5 x 3
    ##   word         sentiment type 
    ##   <chr>        <chr>     <chr>
    ## 1 magnificence positive  Bing 
    ## 2 irritating   negative  Bing 
    ## 3 bastards     negative  Bing 
    ## 4 eccentricity negative  Bing 
    ## 5 breakups     negative  Bing

    ## # A tibble: 5 x 3
    ##   word            sentiment   type    
    ##   <chr>           <chr>       <chr>   
    ## 1 anticipate      uncertainty Loughran
    ## 2 monopolize      negative    Loughran
    ## 3 probationers    litigious   Loughran
    ## 4 distinctiveness positive    Loughran
    ## 5 sued            negative    Loughran

    ## # A tibble: 5 x 5
    ##   word    president score occassion                 type  
    ##   <chr>   <chr>     <dbl> <chr>                     <chr> 
    ## 1 moral   obama         2 Selma                     pressy
    ## 2 serve   obama         1 Usama Bin Laden (2011)    pressy
    ## 3 economy obama         3 SOTU                      pressy
    ## 4 will    obama         3 SOTU_15                   pressy
    ## 5 forget  obama        -1 Immigration Reform (2013) pressy

| word        | value | type  |
| :---------- | ----: | :---- |
| commitment  |     2 | Afinn |
| hiding      |   \-1 | Afinn |
| restricting |   \-2 | Afinn |

A subset of our system.

| word       | sentiment    |
| :--------- | :----------- |
| complexity | negative     |
| offset     | anticipation |
| evict      | sadness      |
| parasite   | fear         |
| marry      | surprise     |

A subset of our system.

## Including Plots

Here is the big plot that loos super
messy.

![](README_files/figure-gfm/pressure-1.png)<!-- -->![](README_files/figure-gfm/pressure-2.png)<!-- -->![](https://i.kym-cdn.com/photos/images/newsfeed/000/598/653/75f.jpg)<!-- -->

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
