# obscurepackage

`obscurepackage` is a tiny R package used for teaching reproducible environments.  
It contains one function, `none_transform()`, which simply returns its input unchanged.

## Installation

```r
devtools::install_github("stellaprins/obscurepackage")
```

## Usage

```r
library(obscurepackage)

# returns the input unchanged
none_transform(1:5)

# works with any object
none_transform("hello world")
none_transform(123)
none_transform(TRUE)
none_transform(list(a = 1, b = "text"))
none_transform(data.frame(x = 1:3, y = c("a", "b", "c")))
```
