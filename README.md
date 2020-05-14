# State of Segregation in the SCAG Region

## To Do: 
1) Create perfomance dictionary:
Both math and ela datasets have matching 'student group' columns to indicate the specified groups' performance in those categories. These datasets include district and school level data. We can slice the data down to the district level and combine the respective performance indicator `currstatus`. Might also use `statuslevel`.

2) Incorporate FRPM data
data only at the individual school level, will need to be averaged, incorporated some other way. The purpose of including this data is because scholars/policy makers occasionally use it as a proxy for segregation indices, so we want to incorporate it in a way that will be comparable to the segregation indices provided by the PySAL segregation package. 

3) Sort lcff funding data: the lcff dataframe has a number of issues. There are more entries in the lcff DF than in the district GDF we want to merge it with. The county code number is not consistent with FIPS codes, ruling it out as a shared 'merging' collumn. We might be able to use the Local Educational Agency or the District Code. Additionally, there are several funding sources in the lcff dataframe, we need to understand which are relevant to the study. 

4) Incorporate all data from the above steps into the school district geodataframe along with the census data from the geosnap module. (as a community?)

5) Run segregation indices - create 'internal' units of school districts with census tracts
5a) validate FRMP as a stand in for segregation
5b) evaluate equity of LCFF allocation through achievement gaps between districts (weigh with segregation)
5c) 

## Purpose
This project harmonizes funding data from the California Local Control Funding Formula (LCFF), Performance data from the California Education dashboard (english language arts and math), school district shapefiles, and census data. The purpose of this harmonization is to investigate the link between the enactment of LCFF and student achievement. Specifically, we seek to explain achievment gaps in historically segregated districts through the lack of funding provided by LCFF.

## Methods

## Findings

## Discussion