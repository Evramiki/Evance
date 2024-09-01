---
title: "my first R markdown"
author: "Miki ngong"
date: "`r Sys.Date()`"
output:
  word_document: default
  html_document: default
---

---

this is my first r markdown document

lets load some data

```{r}
library(datasets)
data("airquality")
summary(airquality)
```

here is pairs plot of the data
```{r}
pairs(airquality)
```

here is the mean of the data

```{r}
mean(airquality)
```






