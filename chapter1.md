---
title: Template Chapter 1
description: >-
  This is a template chapter.


---
## Ex 1.1

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: b0af853e70
```

Do some data science.

`@instructions`


`@hint`



`@sample_code`
```{r}
library(tibble)
library(readr)
data.df <- read_csv("dectrees.csv",
  col_types = cols(
  referrer = col_character(),
  location = col_character(),
  read_faq = col_character(),
  pages_viewed = col_integer(),
  service_chosen = col_factor(levels = NULL)
)
```
`@solution`
```{r}
library(tibble)

```





