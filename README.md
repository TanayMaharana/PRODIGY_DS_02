# PRODIGY_DS_02
# Beverage Production Quality Analysis

## Overview

As a quality analyst in a leading beverage company, the objective is to assess the production lines to ensure they meet industrial standards. The focus is on evaluating the quantity and carbonation levels in the beverages produced, considering factors such as time limits and potential outliers.

## Problem Statement

The primary challenges addressed in this analysis include:
- Assessing the quantity of beverages poured by different production lines.
- Handling outliers in the carbonation levels.
- Investigating extreme carbonation values for appropriate treatment.

## Data Insights

### Quantity Analysis

- Observed approximately normal distribution within quantity.
- Outliers present in CO2 dissolved affecting the normal distribution.
- Extreme carbonation values identified as unreasonable, requiring further treatment.

### Time and Quantity Relationship

- When the time limit was crossed, Assembly line A poured slightly more on average.
- Time limit not crossed, both Assembly Lines A and B had similar average quantities.
- Proportion of Assembly Line B to Assembly Line A is 63.00% to 37.00% when the time limit is crossed.

### Time and Probability Analysis

- When the time limit is crossed:
  - Probability of 10 bottles crossing the time limit on Assembly Line A: 14.70%
  - Probability of 10 bottles crossing the time limit on Assembly Line B: 21.65%
- Probability of at least 10 bottles crossing the limit out of 50 on Assembly Line A: 19.18%
- Probability of at least 10 bottles crossing the limit out of 50 on Assembly Line B: 66.60%

### Quantity Probability

- Probability of bottle content being penalized or having spillage: 1.0%
- Probability of bottle content ranging between 1.95 lts and 2.05 lts: 69.97%
- 90% interval estimate for the Quantity variable: (1.99, 2.00) lts

## Recommendations

Based on the analysis, the following recommendations are made:
- Further, investigate Assembly Line B to understand the reasons for prolonged time.
- Develop strategies to handle outliers in carbonation levels.
- Implement corrective measures for extreme carbonation values.

## Insights

#### 1. Higher Processing Time: In our analysis, we have witnessed that assembly line B has a higher chance of introducing latency in filling the bottles as compared to assembly line A. This definitely has a negative impact on our overall production as it slows down the production rate and therefore can affect the final shipment.

#### The recommendation over here is to investigate the root cause ASAP. This may include fixing or upgrading the components involved in the production line, updating the softwares involved, etc. 
![image](https://github.com/TanayMaharana/PRODIGY_DS_02/assets/105596561/690964c3-8528-4097-8c23-809947933afd)


#### 2. Higher Carbonation: In our analysis, we have encountered certain problems with CO2 dissolved or carbonation analysis. If you conduct further analysis on this variable as suggested in challenges, you will find that the carbonation values are very high (>15 gms per litre). Furthermore, there are 24.85% chances of getting high carbonation which may lead to higher spillage upon opening the bottle.

#### This issue needs to be addressed immediately. Understand that it could be a data issue as well since there were outliers registered in CO2 dissolved and therefore, we may need to collect other samples to conclude things later on.
![image](https://github.com/TanayMaharana/PRODIGY_DS_02/assets/105596561/84b29afe-ad37-4a45-a724-0eade7153b58)


