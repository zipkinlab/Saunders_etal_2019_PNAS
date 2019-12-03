# [Multiscale seasonal factors drive the size of winter monarch colonies](https://www.pnas.org/content/116/17/8609.full)

### Sarah P. Saunders, Leslie Ries, Naresh Neupane, M. Isabel Ramirez, Eligio Garcia-Serrano, Eduardo Rendon-Salinas, & Elise F. Zipkin

### Proceedings of the National Academy of Sciences of the United States of America 

### Please contact the first author for questions about the code or data: Sarah P. Saunders (sarahpsaunders@gmail.com)
________________________________________________________________________________________________________________________________________
## Abstract:
Monarch butterflies in eastern North America have declined by 84% on Mexican wintering grounds since the observed peak in 1996. However, coarse-scale population indices from northern US breeding grounds do not show a consistent downward trend. This discrepancy has led to speculation that autumn migration may be a critical limiting period. We address this hypothesis by examining the role of multiscale processes impacting monarchs during autumn, assessed using arrival abundances at all known winter colony sites over a 12-y period (2004–2015). We quantified effects of continental-scale (climate, landscape greenness, and disease) and local-scale (colony habitat quality) drivers of spatiotemporal trends in winter colony sizes. We also included effects of peak summer and migratory population indices. Our results demonstrate that higher summer abundance on northern breeding grounds led to larger winter colonies as did greener autumns, a proxy for increased nectar availability in southern US floral corridors. Colony sizes were also positively correlated with the amount of local dense forest cover and whether they were located within the Monarch Butterfly Biosphere Reserve, but were not influenced by disease rates. Although we demonstrate a demographic link between summer and fine-scale winter population sizes, we also reveal that conditions experienced during, and at the culmination of, autumn migration impact annual dynamics. Monarchs face a growing threat if floral resources and winter habitat availability diminish under climate change. Our study tackles a long-standing gap in the monarch’s annual cycle and highlights the importance of evaluating migratory conditions to understand mechanisms governing long-term population trends.

## Code 
1. [Monarch_FallModel.R](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/Monarch_FallModel.R): Data management and manipulation code of datasets, as well as code to run hierarchical hurdle model (via JAGS through R). 

2. [top_model_covs.txt](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/top_model_covs.txt): Text file of JAGS model code for the colony-level hurdle model.

## Data

1) [SiteYear_Fall.csv](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/SiteYear_Fall.csv): Data file of site-year variables included in the hurdle modeling of monarch winter colonies.

2) [Site_Fall.csv](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/Site_Fall.csv): Date file of site-specific variables included in the hurdle modeling of monarch winter colonies.

3) [SurveyData_Fall.csv](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/SurveyData_Fall.csv): Data file of monarch colony survey data organized by site and year.

4) [Year_Fall.csv](https://github.com/zipkinlab/Saunders_etal_2019_PNAS/blob/master/Year_Fall.csv): Data file of year-specific variables included in the hurdle modeling of monarch winter colonies.

Note: There is a typo in the published SI. The coordinates of Regions 1 and 2 should be: 105°W, 40°N and 90°W, 30°N (R1) and 105°W, 30°N and 95°W, 20°N (R2). The SI uploaded here has been coorected.
