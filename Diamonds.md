Diamonds DataSet
========================================================
author: Tushar Kathe
date: 09-02-2017
autosize: true

Overview
========================================================
<font size="5">
The application helps choose Diamonds based on user Input                                               
User Selects the Characteristics of the Diamond

- Cut
- Carat
- Price
- Color
- Clarity

Based on user selection the table is diplayed withe the appropriate values filtered from the Diamonds Data set.

Diamonds - Shiny App is hosted on                                                                       
https://tushar1973.shinyapps.io/shiny_diamond_app/

Source code for ui.R and server.R files are available on the GitHub repo:                               
https://github.com/tusharkathe/Shiny_Application

</font>

Diamonds Dataset
========================================================

We use only the First 7 columns from the dataset as they are the most relvant for the application
and selection for Diamonds


```r
library(ggplot2)
head(diamonds)[1:7]
```

```
# A tibble: 6 × 7
  carat       cut color clarity depth table price
  <dbl>     <ord> <ord>   <ord> <dbl> <dbl> <int>
1  0.23     Ideal     E     SI2  61.5    55   326
2  0.21   Premium     E     SI1  59.8    61   326
3  0.23      Good     E     VS1  56.9    65   327
4  0.29   Premium     I     VS2  62.4    58   334
5  0.31      Good     J     SI2  63.3    58   335
6  0.24 Very Good     J    VVS2  62.8    57   336
```

Diamond Price per Carat according Color
========================================================

![plot of chunk unnamed-chunk-2](Diamonds-figure/unnamed-chunk-2-1.png)


Application Screenshot
========================================================

Based on user selection the table is diplayed withe the appropriate values filtered from the Diamonds Data set.                

Shiny Application: Diamond DataSet
 https://tushar1973.shinyapps.io/shiny_diamond_app/

![Applicatoin Screenshot](figures/diamonapp.png)

