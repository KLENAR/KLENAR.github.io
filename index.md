---
title       : IRT example Application 
subtitle    : Course project for the "Developing Data Products"
author      : RE
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---
## Motivation

 
 Situation:
 
 A Professor offers a course on Calculus
 
 
 
 
 Problem:
 
  How can Professor find out which students have sufficiently understood the material?
 
 
 
 Solution:

 Exams!  Students need to take a test with questions on Calculus




---

## Two Parameter Logistic Model

Item response theory (*IRT*) is concerned with accurate test scoring and development of test items. 


The Application use ltm package https://cran.r-project.org/web/packages/ltm/ltm.pdf.

and Two Parameter Logistic Model:

$$\log\frac{P_i(\theta)}{1 - P_i(\theta)}= \alpha_i(\theta-\beta_i)$$,

$P_i(\theta)$ - probability of Correct Response

$i$ denotes the item

Parameters:

* item difficulty parameter: $\beta_i$

* item discrimination parameter: $\alpha_i$

* student ability parameter: $\theta$

---
## Data Set And  Processing

On activate the application do with demo data set from table:


```
##          item1 item2 item3 item4
## Student1     0     0     0     1
## Student2     0     1     0     1
## Student3     0     1     1     1
## Student4     0     1     1     0
## Student4     1     1     1     0
```

Data is fantastic, so we  see poor results but nice pictures!!

But... !!!

User can load and reload his own files from local computer.

User can choose nesessary parameters of his file *.csv


You can try the application here:

 (https://klenar.shinyapps.io/IRTexample)

--- &checkbox

## Results


What do you mind the application show:

1. _data set_

2. _results of Descriptive Analyses of data set (Student's Test Results)_

3. _plot Item Characteristic Curves_

4. _ability estimates_

5. _fit of model objects (summary)_

6. Mars' surface


*** .hint

You just see some words


*** .explanation

One cannot embrace the unembraceable








