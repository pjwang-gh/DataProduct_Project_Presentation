---
title       : MPG Prediction Using Car Weight
subtitle    : Developing Data Products Project
author      : PWang
job         : Coursera Data Science Course 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

### What this App does?
This App predicts the MPG (miles per gallon) of cars using car weight. 

### Data source
The data are from the data package *mtcars* from R, which is also called Motor Trend Car Road Tests. This data was extracted from the 1974 *Motor Trend* US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models). 

--- .class #id 

## Support Documentation for App

The MPG prediction App predicts the MPG of a car using the weight of the car as the predictor.

- Move the slider to change the car weight input (in tons)
- The results of the prediction are shown on the right panel
- A graph is displayed on the right panel with the MPG values in the y-axis and the car weight values in the x-axis
- An orange mark is placed at the predicted value on the regression line
- The car weight (in tons) value may be changed to see how the predicted value and the graph are updated

--- 

## Demo for the App - Inputs

The weight value of a car can be input by moving the slider.

![Input](assets/img/input-example.png)


The responding MPG outcome for the car with the input weight is predicted.


```
## [1] 21.25
```

--- 

## Demo for the App - Regression Model and Prediction Outputs

The orange dots give the prediction of the MPG with the input car weight.
<img src="assets/fig/unnamed-chunk-2.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />






