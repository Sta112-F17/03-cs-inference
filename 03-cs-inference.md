# Inference
Student Name  
November 2, 2017  



## Setup

### Load packages


```r
library(tidyverse)
library(infer)
```

### Kissing

One of the earliest examples of behavioral asymmetry is a preference in humans for turning the head to the right, rather than to the left, during the final weeks of gestation and for the first 6 months after birth.This is thought to influence subsequent development of perceptual and motor preferences. A study of 124 couples found that 64.5% turned their heads to the right when kissing. 


```r
kissing <- read_csv("data/kissing.csv")
```

1. Do these data provide convincing evidence (at the 5% significance level) that majority of couples turn their heads to the right when kissing?

2. Construct a 90% confidence interval for the proportion of couples who turn their heads to the right when kissing. Interpret the interval in context of the data.

3. Do the confidence interval and the hypothesis test agree? Why or why not?

### Course evaluations

You're familiar with this dataset already.


```r
evals <- read_csv("data/evals-mod.csv")
```

1. Pick a categorical variable with 2 levels (or use subsetting or recoding to make a variable of interest into 2 levels). Conduct a hypothesis test (at the 5% significance level) comparing the mean evaluation scores of the two groups.

2. Construct a 95% confidence interval for the difference between the average evaluation scores of the two groups from the previous question. Interpret the interval in context of the data.

3. Do the confidence interval and the hypothesis test agree? Why or why not?
