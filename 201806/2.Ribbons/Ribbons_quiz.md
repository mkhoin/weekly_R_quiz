Q) geom_polygon, geom_ribbon, geom_area, geom_path 를 이용하여 4개의 리본을 그려주세요!  

```{r, message=FALSE, warning=FALSE, include=FALSE}
library(ggplot2)
library(gridExtra)

# plot base
g <- 
  ggplot() + 
  theme_classic() + 
  theme(axis.title = element_blank())
```

![target!](Ribbons_result.PNG)
