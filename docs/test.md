Test
================

``` r
library(tidyverse)
## Warning: package 'tidyr' was built under R version 3.6.3
## Warning: package 'dplyr' was built under R version 3.6.3
strategies <- data.frame(ID = c(1, 2, 3, 4, 5),
                         Text = c("Test 1", "Test 2", "Test 3",
                                  "Test 4", "Test 5"))

print(as.character(strategies$Text[which(strategies$ID == sample(1:5, 1))]),
      quote = FALSE)
```

\[1\] Test 5
