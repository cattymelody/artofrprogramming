# Getting started

## 1.3 Introduction to functions

Given the code below, what is the final value of *x*?


```{r}
x <- 5L
super.assigner <- function(n = 8) {
  x <<- 10L * n
}
super.assigner(x)
x
```

> 50

What about now? What would you expect *x* to be?

```{r}
x <- 5
super.assigner <- function(n = 8) {
  n * 1
}
x <- super.assigner()
x
```

> 8



## 1.7 Getting help

A student would like to use the `rnorm()` function.
Provide at least two ways the student can seek help within the R environment.

> ?rnorm

> help(rnorm)

> example(rnorm)

> help.search("rnorm")
