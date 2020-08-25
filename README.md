# LCFF Policy Analysis

[updated shapefile set](https://gis.data.ca.gov/datasets/e9476c422f0842a7a38652aaf4c7597c_0?geometry=-174.879%2C31.049%2C-63.126%2C43.258) This data was not available to us for the original analysis.



## Background / previous work
Previously, this project created treatment and control groups for school districts based on their concentration grant status (as determined by their share of high needs students among the district's student body). Districts with 55% or higher high needs students were coded as treatment = 1, while districts under that threshold were coded as treatment = 0. This 'naive' regression of student test scores (english and math, seperately) on the interaction effect of per-capita funding from the state (determined by total funding / number of students enrolled) and the dummy treatment variable indicating the receipt of a concentration grant yielded small but statistically significant coefficients. 

Effectively, we found that the targetted student groups (english language learner, hispanic, and SES-disadvantaged students) in districts that recieved a concentration grant tended to have higher scores than the same student groups in districts that did not recieve the concentration grant (just give the schools more money, forehead).

## Goal
The next step is to incorporate regression discontinuity designs into this analysis. I want to narrow the sample population to pair districts that are most similar aside from their treatment variable. 


### Geographic similarity
Want to view districts within the same county. Can try to find pairs that are geographic neighbors (shared line) using geopandas.

### Demographic similarity
Want to merge geometry data with demographic data. Does census data exist at the school district level? If not, dissolve census tracts into the school districts? Or use county data to represent all districts in the county? This doesn't seem too different from geographic similarity, but maybe if some counties are similar demographically, the districts within those counties can be compared to each other.
- population total
- % white
- % latino/hispanic
- income brackets



git checkout output?

>`$ git checkout new`
>
>`Switched to branch 'new'`
>
>`M       rdd.ipynb`

Multiple pairings vs unique pairing.
student's environment vs broader neighboring enviornment.
stable vs stable neighborhoods, turnover


to do:
histogram/density

Spatial autocorrelation tests - is the distribution random in space?
build weight structure - defines whos a neighbor of who

pandas pivot! 

import to env

pandas
geopandas
pysal 
legendgram channel?
jupyter channel?
