---
title       : dataProducts App
subtitle    : Assignment for the course 'Developing Data Products'
author      : cosmasquantum
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

### Purpose
This app is a visualization platform for the data set 'mtcars'. The corresponding data set is part of the 'datasets' package.

### Specifications 

The task of this app is to provide plots of two preselected variables of the data set. The app consists of a sidebar panel for input selection and a main panel for the output plot. In the sidebar panel, the user can select the size of the data to be used (Sample Size) and the two variables for the plot (X,Y). In addition, the user can select a Facet in order to group the data according to one of the variables in the data set.

--- .class #id 

## The data set

### Description
The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models).


```r
head(mtcars)
```

```
##                    mpg cyl disp  hp drat    wt  qsec vs am gear carb
## Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
## Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
## Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
## Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
## Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
## Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

--- .class #id 

## The App

<img src="FireShot Capture 1 -  - https___cosmasquantum.shinyapps.io_dataProducts.pdf" height="700px" width="1000px" />

--- .class #id

## Get started

### [Link to the App][id]

### [GitHub Repository][id2]
 

[id]: https://cosmasquantum.shinyapps.io/dataProducts

[id2]: https://github.com/cosmasquantum/dataProducts
