# R-
# Visualizing: `ggplot2` {#ggplot2}

Why do we start with data visualization? Not only is data viz a big part of analysis, it’s a way to SEE your progress as you learn to code.

> "ggplot2 implements the grammar of graphics, a coherent system for describing and building graphs. With ggplot2, you can do more faster by learning one system and applying it in many places." - [R4DS](http://r4ds.had.co.nz/data-visualisation.html)

This lesson borrows heavily from Hadley Wickham's [R for Data Science book](http://r4ds.had.co.nz/data-visualisation.html), and an EcoDataScience lesson on Data Visualization.

```{r viz ops, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, warning = F, message = F)
library(htmltools)
```

## Objectives & Resources

### Objectives

- install our first package, `ggplot2`, by installing `tidyverse`
- learn ggplot2 with a national parks visitation dataset (important to play with other data than your own, you'll learn something.)
- practice writing a script in RMarkdown
- practice the rstudio-github workflow

### Resources

Here are some additional resources for data visualization in R:  

- [ggplot2-cheatsheet-2.1.pdf](https://www.rstudio.com/wp-content/uploads/2016/11/ggplot2-cheatsheet-2.1.pdf)  
- [Interactive Plots and Maps - Environmental Informatics](http://ucsb-bren.github.io/env-info/wk06_widgets.html)  
- [Graphs with ggplot2 - Cookbook for R](http://www.cookbook-r.com/Graphs/#graphs-with-ggplot2)  
- [ggplot2 Essentials - STHDA](http://www.sthda.com/english/wiki/ggplot2-essentials)  
- ["Why I use ggplot2" - David Robinson Blog Post](http://varianceexplained.org/r/why-I-use-ggplot2/)
- Melanie Frazier's [GitHub Lesson at University of Queensland](https://github.com/OHI-Science/data-science-training/blob/master/ggplot2_mel.Rmd)
