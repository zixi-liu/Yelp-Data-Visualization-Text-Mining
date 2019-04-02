# Yelp-Data-Visualization-Text-Mining
```{r}
library(dplyr) #data manipulation
library(ggplot2) #visualizations
library(gridExtra) #viewing multiple plots together

business <- readRDS("business.RDS")
str(business)
review <- readRDS("review.RDS")
str(review)
```
