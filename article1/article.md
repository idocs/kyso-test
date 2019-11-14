---
title: First Article
description: This is a short description
output:
  html_document:
    keep_md: true
    preserve_yaml: true
---





```r
ggplot(mtcars, aes(x = wt, y = mpg)) +
  geom_point() +
  theme_gray(base_size = 18, base_family = 'Lato')
```

![](article_files/figure-html/plot-1-1.png)<!-- -->

