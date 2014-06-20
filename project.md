Machine Learning Course Project
========================================================

This is an R Markdown document. Markdown is a simple formatting syntax for authoring web pages (click the **Help** toolbar button for more details on using R Markdown).

When you click the **Knit HTML** button a web page will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

Downloading the datasets from internet (source = http://groupware.les.inf.puc-rio.br/har)

```r
download.file('https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv',destfile='pml-training.csv',method='curl')
download.file('https://d396qusza40orc.cloudfront.net/predmachlearn/pml-testing.csv',destfile='pml-testing.csv',method='curl')
summary(cars)
```

```
##      speed           dist    
##  Min.   : 4.0   Min.   :  2  
##  1st Qu.:12.0   1st Qu.: 26  
##  Median :15.0   Median : 36  
##  Mean   :15.4   Mean   : 43  
##  3rd Qu.:19.0   3rd Qu.: 56  
##  Max.   :25.0   Max.   :120
```

###Cleanning the dataset
You can also embed plots, for example:


```r
plot(cars)
```

![plot of chunk unnamed-chunk-2](figure/unnamed-chunk-2.png) 

