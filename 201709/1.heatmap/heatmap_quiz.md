Q) 주어진 데이터를 이용해서 차트를 그려주세요 :)  

![target!](heatmap_result.PNG)  

```{r, message=FALSE, warning=FALSE, include=FALSE}
library(dplyr)
library(data.table)
library(ggplot2)

set.seed(1986)

raw.data <- 
  data.frame(
    product = sample(rep(LETTERS[c(1:4)],c(30,40,30,20))))%>%
  mutate(
    making.year = sample(rep(2017:2014,c(30,40,30,20))),
    repair.year = making.year+sample(1:4)) %>%
  arrange(product, making.year, repair.year)
```
