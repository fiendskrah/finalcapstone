# State of Segregation in the SCAG Region

## To Do / datawork
1) Create _attribute dictionary(?)_ with **perfomance data**
[`ela` file and layout](https://www.cde.ca.gov/ta/ac/cm/ela18.asp).
[`math` file and layout](https://www.cde.ca.gov/ta/ac/cm/math18.asp).

Both math and ela datasets have matching `studentgroup` columns to indicate performance by those groups in math and English language arts. We can aggregate the data to the district level and use the performance indicator `currstatus`, which is a measure of deviation from the average student to evaluate lcff. 



2) Incorporate all data into single geodataframe
from the above steps into the school district shapefile dataframe along with the census data from the geosnap module. (as a community?)


3) Analysis
  * 3a) evaluate performance of groups in a district in relation to that group's performance statewide. 

  * 3b) validate FRMP as a proxy for segregation
  * 3c) evaluate equity of LCFF allocation through achievement gaps between districts (weigh with segregation + income)

> **Deliverable**
>1) County and district dictionaries with the structure: 
`dict = {studentgroup;`
    `currstatus, priorstatus, change, currdenom}`  
>2) District choropleth maps of deviation of performance by `studentgroup` in English language arts and math. 

Performance variables 
* Keep 
  * `currstatus`: average distance from Standard of students who took the Smarter Balanced summative assessment. 
  * `currdenom`: number of students who took the assessment.
  * `priorstatus`: last year's 'currstatus'.
`change`: difference between this year's and last year's 'currstatus'

* Discard
  * `curradjustment`: The number of points removed from the current year status due to the participation rate being below 95% *only group with adjusted scores due to lower participation rate is foster youth (curradjustment)*


## Free (and) Reduced Price Meal (`frpm`) data
[2018-2019 file structure information](https://www.cde.ca.gov/ds/sd/sd/filessp.asp)

Scholars/policy makers use the  as a proxy for segregation indices, so we include it to  compare to the segregation indices provided by the PySAL segregation package. We will also include it in the attribute dictionary to describe districts in the context of poverty, performance, and funding.

Data can be aggregated by `District Code`.

> Students are classified as *low income* based on if they qualify for free or reduced-price meals. In many cases, students are determined FRPM-eligible through an application process sent to students’ households. If a household’s income is below 185 percent of the federal poverty line *($43,568 for a family of four)*, the student is eligible for FRPM. In other cases, students are directly certified as FRPM-eligible due to participation in other social service programs, such as the California Work Opportunity and Responsibility to Kids program. Foster youth automatically are eligible for FRPM, therefore the foster family’s income has no bearing on the foster student’s FRPM eligibility.

> do: *Application based process suggests that undocumented students will be missed due to fear around providing information to government - verify with census data? Can make differentiation between 'Free' and 'free and reduced lunch' in terms of poverty vs extreme poverty - sclice both.*

## Local Control Funding Formula (`lcff`)  data
[File location](https://ias.cde.ca.gov/lcffsnapshot/lcff.aspx) <br>[F.A.Q.(documentation)](https://www.cde.ca.gov/fg/aa/lc/lcfffaq.asp#FC)

Focus are three major grant sources: base, supplemental, and concentration.
<br>The `base_grant` varies by grade level and is keyed to the average daily attendance (ADA) of students in four grade spans: K–3, 4–6, 7–8, and 9–12. K–3 and 9–12 receive additional funding to support smaller class sizes and career technical education (CTE). all districts recieve a base grant.
<br>The `supplemental_grant` is equal to 20 percent of the adjusted base grants multiplied by the LEA’s unduplicated percentage of English learners, income eligible for free or reduced-price meals, and foster youth pupils.
<br>The `concentration_grant` is equal to 50 percent of the adjusted base grants multiplied by an LEA’s percentage of unduplicated pupils above 55 percent. Not all schools get a concentration grant.

> do: address mismatch in number of districts between datasets for lcff, performance, frpm, shapefiles. 

> The _Unduplicated_ count of pupils who (1) are English learners, (2) meet income or categorical eligibility requirements for free or reduced-price meals under the National School Lunch Program, or (3) are foster youth. “Unduplicated count” means that each pupil is counted only once even if the pupil meets more than one of these criteria 
>(EC sections 2574(b)(2) and 42238.02(b)(1)).
If many students in the district potentially fall into more than one of these groups, their disadvantages are compounded, and the district may have a greater need as a result.

___
## Paper Draft
### Purpose
This project harmonizes funding data from the California Local Control Funding Formula (LCFF), Performance data from the California Education dashboard (english language arts and math), school district shapefiles, and census data. The purpose of this harmonization is to investigate the link between the enactment of LCFF and student achievement. Specifically, we seek to explain achievment gaps in historically segregated districts through the lack of funding provided by LCFF.

### Data and Sources
#### English Language Arts and Math performance datasets
Key performance indicator: `currstatus`
From [California Department of Eduation's website](https://www.cde.ca.gov/ta/tg/sa/sbacsummative.asp)
>The Smarter Balanced Summative Assessments are comprehensive, end-of-year assessments for English language arts/literacy (ELA) and mathematics that are aligned with the Common Core State Standards (CCSS) for English language arts/literacy (ELA) and mathematics and measure progress toward college and career readiness. The tests capitalize on the strengths of computer adaptive testing—efficient and precise measurement across the full range of achievement and the timely turnaround of results.

These datasets include the 58 County Offices of Education. From [California Department of Eduation's's website](https://www.cde.ca.gov/re/sd/co/coes.asp):
>County offices of education support school districts by performing tasks that can be done more efficiently and economically at the county level. County offices provide or help formulate new curricula, staff development and training programs, and instructional procedures; design business and personnel systems; and perform many other services to meet changing needs and requirements. When economic or technical conditions make county or regional services most appropriate for students, county offices provide a wide range of services, including special and vocational education, programs for youths at risk of failure, and instruction in juvenile detention facilities.
Some COE's might reasonably perform testing for certain student groups, but for many of the COEs in this dataset, `currstatus` values are missing from many `studentgroup`. 
We remove COE's from our analysis

#### LCFF dataset
Unlike both performance datasets or the frpm dataset, the lcff dataset does not have a district or county name attribute, instead it uses a Local Eduational Agency.

### Methods
#### Data cleaning/synthesis

### Findings

_State level performance distribution for AY 18-19_
<br>Highest groups are Asian (62.4), Filipino (44.0), multiple races (28.6), and white (27.7). All student's currstatus is -6. The groups determining the allocation of LCFF funding are English learners, homeless and foster youth, 

_Free and reduced meal distribution_
<br>
### Discussion

## Presentation notes
- context around implementation of lcff.
  - how did the groups that are considered for extra funding become the focus? Is that right?
  - intention of lcff - where _should_ the money be going?
  - What factors contribute to increased student perfomance?

- clarify questions and purpose
  - equity
  - cost effectiveness
  
- methods
  - list and describe datasets and manipulation
  - segregation indices and frpm allignment

- delieverables 
  - legend is important
  - need key findings slide 