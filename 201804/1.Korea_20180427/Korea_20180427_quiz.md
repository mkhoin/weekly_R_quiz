Q) 통일한국은 과연 우리의 미래가 될 수 있을까요?  

주어진 데이터를 이용하여... 그려봅시다 :)  

```{r, message=FALSE, warning=FALSE, include=FALSE}
library(ggplot2)

korea <-
  map_data('world') %>% 
  filter(region %in% c('North Korea','South Korea'))
```

![target!](Korea_20180427_result.PNG)
