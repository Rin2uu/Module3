---
title: "Module 3- HTML Document"
author: "Prashant Dey"
date: "11/12/2018"
output: 
  html_document: 
    css: style.css
    df_print: kable
    fig_height: 6
    fig_width: 6
    toc: yes
    toc_float: true
    keep_md: true
    code_folding: hide
---



## R Markdown {#nextsteps .emphasized}

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


```r
plot(cars)
```

![](html_document_files/figure-html/unnamed-chunk-1-1.png)<!-- -->

## Including Plots

You can also embed plots, for example:

![](html_document_files/figure-html/pressure-1.png)<!-- -->

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.


```r
head(cars)
```

<div class="kable-table">

 speed   dist
------  -----
     4      2
     4     10
     7      4
     7     22
     8     16
     9     10

</div>

