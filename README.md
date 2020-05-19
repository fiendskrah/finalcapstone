# State of Segregation in the SCAG Region

## To Do: 
### 1) Create dictionary with perfomance data
Both math and ela datasets have matching 'student group' columns to indicate the specified groups' performance in those categories. These datasets include district and school level data. We can slice the data down to the district level and combine the respective performance indicator `currstatus`, which is a measure of standard deviation? See the [ELA](https://www.cde.ca.gov/ta/ac/cm/ela18.asp) and [math](https://www.cde.ca.gov/ta/ac/cm/math18.asp) file layout.

### 2) Incorporate FRPM data
See the [2018-2019 file structure information](https://www.cde.ca.gov/ds/sd/sd/filessp.asp)
data only at the individual school level, will need to be averaged, incorporated some other way. The purpose of including this data is because scholars/policy makers occasionally use it as a proxy for segregation indices, so we want to incorporate it in a way that will be comparable to the segregation indices provided by the PySAL segregation package.
2a) Remove % sign from strings
2b) convert strings to integers
2c) aggregate up to district level using pandas.groupby
2d) average (?) scores from schools to get FRPM figure district wide. Weigh by total school attendence? (?)

*Students are classified as “low income” based on if they qualify for free or reduced-price meals (FRPM). In many cases, students are determined FRPM-eligible through an application process sent to students’ households. If a household’s income is below 185 percent of the federal poverty line ($43,568 for a family of four), the student is eligible for FRPM. In other cases, students are directly certified as FRPM-eligible due to participation in other social service programs, such as the California Work Opportunity and Responsibility to Kids program. Foster youth automatically are eligible for FRPM, therefore the foster family’s income has no bearing on the foster student’s FRPM eligibility*

Application based process suggests that undocumented students will be missed due to fear around providing information to government
Can make differentiation between 'Free' and 'free and reduced lunch' in terms of poverty vs extreme poverty.

### 3) Sort lcff funding data
[File location and information](https://ias.cde.ca.gov/lcffsnapshot/lcff.aspx)
the lcff dataframe has a number of issues. There are more entries in the lcff DF than in the district GDF we want to merge it with. The county code number is not consistent with FIPS codes, ruling it out as a shared 'merging' collumn. We might be able to use the Local Educational Agency or the District Code. Additionally, there are several funding sources in the lcff dataframe, we need to understand which are relevant to the study. 

*The base grant varies by grade level and is keyed to the average daily attendance (ADA) of students in four grade spans: K–3, 4–6, 7–8, and 9–12. K–3 and 9–12 receive additional funding to support smaller class sizes and career technical education (CTE).*

*Primarily looking at three major grant sources: 'Base,' 'Supplemental,' and 'Concentration'. Also good to take 'Total' from this data source.*  

*Unduplicated Pupil Count - students who are low income and/or ELL and/or foster youth, unduplicated. If many students in the district potentially fall into more than one of these groups, their disadvantages are compounded, and the district may have a greater need as a result.*

### 4) Incorporate all data into single geodata frame
from the above steps into the school district geodataframe along with the census data from the geosnap module. (as a community?)

### 5) Analysis
5a) Run segregation indices - create 'internal' units of school districts with census tracts
5b) validate FRMP as a stand in for segregation
5c) evaluate equity of LCFF allocation through achievement gaps between districts (weigh with segregation)
5d) 

## Purpose
This project harmonizes funding data from the California Local Control Funding Formula (LCFF), Performance data from the California Education dashboard (english language arts and math), school district shapefiles, and census data. The purpose of this harmonization is to investigate the link between the enactment of LCFF and student achievement. Specifically, we seek to explain achievment gaps in historically segregated districts through the lack of funding provided by LCFF.

## Data and Sources

## Methods

## Findings

## Discussion