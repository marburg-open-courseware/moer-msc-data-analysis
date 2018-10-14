---
title: "Examples: R Markdown with HTML Output"
toc: true
toc_label: In this example
---

## Below is what the R markdown source looks like
``````yaml
---
title: "Example: R Markdown with html output"
author: "Thomas Nauss"
date: "10 Oktober 2018"
output: html_document
---

## This is a header

This is an R Markdown document. Markdown is a simple formatting syntax for 
authoring HTML, PDF, and MS Word documents. 
For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes 
both content as well as the output of any embedded R code chunks within the 
document. You can embed an R code chunk like this:

```{r}
summary(cars)
```


## This is another header

You can also embed plots, for example:

```{r, echo=FALSE}
plot(cars)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent 
printing of the R code that generated the plot.

``````

## Below is what the R markdown html output looks like

### This is a header

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


```r
summary(cars)
```

```
##      speed           dist       
##  Min.   : 4.0   Min.   :  2.00  
##  1st Qu.:12.0   1st Qu.: 26.00  
##  Median :15.0   Median : 36.00  
##  Mean   :15.4   Mean   : 42.98  
##  3rd Qu.:19.0   3rd Qu.: 56.00  
##  Max.   :25.0   Max.   :120.00
```


### This is another header

You can also embed plots, for example:

![]({{ site.baseurl }}/assets/images/rmd_images/e01-01/unnamed-chunk-2-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.