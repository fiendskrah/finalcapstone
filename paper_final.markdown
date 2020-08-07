# Equity in School Funding: An Analysis of California's Local Control Funding Formula's Concentration Grant

## A Capstone Research Project Presented for the degree of Master of Public Policy to the School of Public Policy, University of California, Riverside
> Mikaila Kruse
>
> Dylan Skrah
>
> Advisor: Dr. Sergio Rey
>
> June 2020

# Introduction/Abstract

In response to the well-understood effects of socioeconomic disadvantage 
on long-term academic performance and by extension, lifetime opportunity
and outcomes of California's students, the state of California enacted
major public school finance reform in the form of SB-97, known as the
Local Control Funding Formula (LCFF), which was signed by Governor Jerry
Brown and codified into law on September 26, 2013. LCFF sought to
simplify the state funding mechanism, increase accountability, and most
importantly, realign school financing to focus on *equity* by directing
more funding to the students who stand to benefit the most from more
educational resources: low-income students, English Learners, and foster
youth. This groundbreaking school finance model seeks to ameliorate the
achievement gaps and low educational outcomes associated with those
disadvantaged student groups in order to uplift whole communities and
foster true social and economic mobility. After six years of
implementation amid a shift in curricula and testing, and after only
being fully funded just last school year (2018-2019), policymakers and
education advocates nationwide are eager to understand the impact of
LCFF on student outcomes. A better understanding of the formula's
effectiveness will determine whether California should stay the course
and if the state's innovative funding scheme can serve as a model for
other states. Due to the importance of length of exposure in analyzing
the effectiveness of policy interventions on student outcomes, this
study is one of the first and few of its kind. This study examines the
link between increased funding and academic performance by synthesizing
a novel dataset using data from the California Department of Education
(CDE) and performing regression analyses. More specifically, we focus
our analysis on the *concentration grant*, one of three major components
of the LCFF, which directs additional funding to school districts with
high concentrations of disadvantaged students. We find statistically
significant, if small, increases in academic performance among student
groups directly targeted by the LCFF. Given that this study uses data
from the only academic year available in which LCFF has been fully
funded, our findings suggest that the formula's *concentration grant* is
having positive effects on targeted groups' academic achievement.

## I.  History of School Funding in California

Before the Local Control Funding Formula was adopted, K-12 schools in
California were funded disproportionally due to the use of property
taxes. Over time the dependence on property taxes was largely abandoned
but funding remained unequal, and even when it became equal in many
respects, policymakers recognized that it was inequitable. For most of
California's history, school funding and oversight was hyper-localized
with a majority of funding coming from property taxes and school boards
holding significant power. Given the disparities in property value and
ability to raise revenue via passage of local measures, low-income
school districts often spent less on public education than wealthier
districts.

One facet of the Civil Rights Movement of the 1960s was to begin to
question the inequitable ways in which public schools were locally
financed. The decision in *Brown V. Board of Education* (1954) set forth
an ideal for equal educational opportunity by determining separate
schooling was unequal. For many education advocates this ruling implied
more than racial desegregation, it implied that disparate funding based
on wealth could also be considered a violation of the equal protection
clause under the Fourteenth Amendment. The argument was that as long as
schools were funded primarily from local property taxes, students living
in areas of high property values would have greater access to
educational resources than their peers in areas with low property
values. By the end of the 1960s, civil rights attorneys across several
states began to challenge this school financing scheme. (Martin, 2006)

California's Supreme Court case, Serrano *v. Priest* was the first to
succeed in its efforts. The California Supreme Court heard *Serrano V.
Priest* in 1971 and determined that California's substantial dependence
on local property taxes and resulting wide disparities in school
revenue, violated the equal protection clause of the Fourteenth
Amendment. Justice Sullivan stated in his opinion: "We have determined
that this funding scheme invidiously discriminates against the poor
because it makes the quality of a child\'s education a function of the
wealth of his parents and neighbors". (Serrano v. Priest, 1971) The
state's first response to this legal opinion was to enact revenue limits
for "high spending districts'', *Serrano V. Priest II* determined this
action still did not address unequal funding. Under legal pressure, the
state legislature in 1977 devised a funding formula that enacted revenue
caps and put state aid in place as a means to equalize funding across
districts. Thus, the funding was equalized across districts in many
respects, but was not made more equitable. The passage of Proposition 13
the following year is often credited as being the linchpin of what is
commonly referred to as the "property tax revolt". Proposition 13
established a 1% limit on the property tax rate and a 2% limit on the
annual increase in the assessed taxable value of an individual property,
essentially protecting property owners from tax increases indefinitely.
(Martin, 2006) Academics and economists have characterized the "property
tax revolt" as a movement by the wealthy in opposition to the court
ordered and state mandated school financial equalization efforts, but
recently scholars such as Martin have refuted this assertion. (Martin,
2006) Nevertheless, Proposition 13 stood to significantly reduce the
amount of local property tax contributions to public schools, leading to
a shift in funding responsibility and oversight to the state.

The next major shift in school funding policy occurred in 1988 when
voters passed Proposition 98 which created a minimum funding requirement
for public schools. Under Proposition 98, the state is required to spend
roughly 40 percent of General Fund revenues on its public schools. Most
school district funding came through Prop 98 in the form of "revenue
limits" in which base funding per pupil was provided and then school
districts with revenues falling short of the limit received state
funding to make up the difference. This was supplemented with state and
federal categorical funding programs that placed restrictions on how the
money was spent (Lafortune, 2019).

## II. The Local Control Funding Formula

In 2013-2014 the state of California adopted the Local Control Funding
Formula (LCFF). This new formula sought to simplify school finance and
provide local flexibility and increased accountability that was
previously absent with categorical funding programs. The new formula
also focused on *equity* rather than *equality* by directing funding
towards the students determined to be "high-needs", these students
typically have lower academic achievement and stand to benefit the most
from an increase in educational resources.

The LCFF formula is divided into three grants; the base grant,
supplemental grant and concentration grant. The *base grant* varies by
grade level but is tied to a school district's Average Daily Attendance
(ADA), providing an equal base amount of funding per student across
school districts. K-3 students receive slightly more money from the base
grant to support smaller class sizes and 9-12 students receive slightly
more funding to support Career Technical Education (CTE).

The *supplemental grant* provides supplemental funding to a school
district equal to 20 percent of the base grant for each high-needs
student in the school district. The three student groups identified as
high needs by the formula are English Language Learners (EL), low-income
students (LI), and foster youth. Students are classified as EL based on
a home language survey and the California English Language Development
Test (CELDT). Once they are determined to be Fluent English Proficient
(FEP) they are no longer counted towards the supplemental grant part of
the formula. Students are classified as "low-income" based on if they
qualify for free or reduced-price meals (FRPM). In many cases, students
are determined FRPM-eligible through an application process sent to
students' households. If a household's income is below 185 percent of
the federal poverty line (\$43,568 for a family of four), the student is
eligible for FRPM. In other cases, students are directly certified as
FRPM-eligible due to participation in other social service programs,
such as the California Work Opportunity and Responsibility to Kids
program. Foster youth automatically are eligible for FRPM; therefore,
the foster family's income has no bearing on the foster student's FRPM
eligibility. (Taylor, 2013) If a student falls into more than one
high-needs category, if they are both low-income and an English Language
Learner for example, they are only counted once in the formula to create
the *unduplicated pupil count*. For context, more than half of
public-school students in California are economically disadvantaged
(low-income), and about a third are English Language Learners (Murphy &
Paluch, 2018).

The *concentration* grant part of the formula is then awarded to those
school districts in which 55 percent or more of the student population
are high needs. For each student above the 55 percent threshold,
districts receive additional funding equal to 50 percent of the base
grant. (Hill and Ugo, 2015) This three-grant system can create large
differences in per pupil funding. In 2018, base LCFF funding was \$48
billion and additional funding for high-need students totaled \$9.5
billion. Concerns about how districts are distributing supplemental
funds have generated proposals for tighter rules on spending. (Murphy
and Paluch, 2018) This sliding scale for funding is believed to be more
equitable because high-needs students and districts receive more funding
than their ![](media/image1.png){width="4.14in" height="3.01in"}peers.
The concentration grant in particular recognizes that producing better
educational outcomes for high-needs students is more challenging in
districts where this population is extremely concentrated.

LCFF allows funds to be spent for any educational purpose but requires
districts to develop Local Control and Accountability Plans (LCAPs) that
detail district goals and document how districts plan to measure their
progress toward those goals. School districts must improve or increase
services for high-need students in proportion to the increased funding
they receive, but they may spend supplemental and concentration grants
on district- and school-wide programs.(Taylor, 2013)

![](media/image2.png){width="4.31in" height="2.74in"}In 2018--19,
California public schools received a total of \$97.2 billion in funding
from three sources: the state (58%), property taxes and other local
sources (32%), and the federal government (9%) (Murphy & Paluch, 2018).
The state of California is unique in the amount of funding it provides
at the state level. California's proportions differ from many other
states that have substantial local property tax revenue that is utilized
to cover a larger share of school funding. Unlike most states,
California's State Constitution, due to the passage of Proposition 13,
limits local property tax rates (Taylor, 2018). Of the 6.2 million K--12
students in California, about nine out of ten attend one of the nearly
9,000 regular schools in 1,026 school districts while the other 11% of
students attend about 1,228 charter schools---which are publicly funded
but not subject to some state regulations. (Murphy & Paluch, 2018)

## III. Disparities in Academic Performance and Educational Outcomes

Researchers, policy makers and advocates in education have long espoused
issues related to equity, particularly as it relates to race, gender,
and socioeconomic status. The Equality of Educational Opportunity
report, commonly referred to as the "Coleman Report" published in 1966,
set the standard for studying public education. It was initially a study
commissioned by the U.S Department of Health, Education and Welfare to
understand where the nation stood in terms of desegregation of public
schools. The extensive report found that a student's family background
(their socioeconomic status) paired with the diversity of socioeconomic
backgrounds of their peers in the classroom, was the biggest determinant
of educational success. Coleman also found that a substantial
achievement gap existed between African-Americans and their White peers,
in which African-American students were often several grade levels
behind in comparison (Coleman et al. 1966). Since then, a myriad of
studies across several decades have confirmed Coleman's findings to
posit that inequalities in opportunity and outcomes along race and
socioeconomic lines begin before a child enters school, persists
throughout their education and on to the rest of their life. Moreover,
these inequalities are more stark in the United States than they are in
comparable countries (Bradbury et al. 2015). Poverty is associated with
many conditions such as low educational attainment of one's parents,
poor nutrition and healthcare, fewer educational resources at home,
weaker preschool education, more exposure to violence and abuse, lack of
availability of resources among other characteristics that lead to lower
educational outcomes for low-income students (Newberger et al. 2011).

![](media/image3.png){width="3.93in" height="2.6354166666666665in"}The
disparity in educational outcomes along socioeconomic and racial lines
is still present today in the state of California. A 2018 LAO report
found a stark disparity in test scores amongst student groups. A
comparison between low-income and non-low-income students found that
only 36 percent of low‑income students met or exceeded the state
standards in eighth grade English language arts, while 68 percent of
non‑low‑income students met or exceeded standards in comparison. The
gaps between students are similar in other grade levels and for math
scores as well. Results on statewide exams show significant achievement
gaps among California's four largest ethnic groups. These gaps persist
even after controlling for income. As the figure shows, low‑income Black
and Hispanic students have lower proficiency rates on eighth grade
English language arts exams (25 percent and 33 percent) than low‑income
White and Asian students (44 percent and 62 percent). Similar
differences among groups exist in third and eleventh grade (Taylor,
2018). When the scores for low-income students are broken down by ethnic
groups, we see a compounding effect in which Black and Hispanic students
are performing even worse than their other low-income peers. Race and
ethnicity is notably not one of the high-need student categories
identified by the LCFF formula to receive more funding, but race and
ethnicity are certainly a consideration for the state and for districts
when ![](media/image4.png){width="4.114583333333333in"
height="2.4270833333333335in"}evaluating achievement gaps and developing
LCAPs to produce better student outcomes . These low-income, low
performing students are captured by the *unduplicated pupil count*, but
the compounding effect of race and ethnicity and income is not captured
by the formula. In addition to low-income students, the LCFF also
determines English Language Learners to be high-needs students due to
the additional barrier of language they must overcome in order to learn.
As mentioned previously, once English Language Learners are determined
to be "fluent proficient" they are no longer counted in the LCFF's
unduplicated pupil count. For the majority of grade levels depicted,
less than 10 percent of English Learners are scoring at or above
standard on standardized tests, justifying the LCFF's prioritization of
this group to receive additional funding to procure more educational
resources.

## IV. Role of Increasing Inequality and Segregation

![](media/image5.png){width="4.15625in"
height="2.2395833333333335in"}Schools with high concentrations of
students in poverty tend to have less experienced teachers, higher
teacher and staff turnover, more remedial and special education classes,
fewer honors and AP classes, lower graduation rates, weak connections to
college etc., further exacerbating the inequalities that exist before a
student enters the classroom (Rothstein, 2004). As mentioned previously,
over half of California's K-12 students are low-income, and a rising
trend of income inequality in recent decades suggests poverty and
concentration/segregation of those living in poverty are expected to
increase. The very high level of student poverty is in part a reflection
of the intense polarization and inequality of incomes in the U.S (Noah,
2012). This signals that worsening student outcomes are to come, as the
Coleman report and numerous studies posit, students' own socioeconomic
background is related to their achievement, but the average
socioeconomic background of their peers in school had an equal effect
and sometimes even greater effect on academic achievement and
educational outcomes than their own individual background (Rumberger &
Palardy, 2005). The increased concentration of low-income students
disproportionately affects Black and Latino students, creating "double
segregation" of race and poverty. An analysis of school composition
trends found the following:

> *The typical Black or Latino today attends school with almost double
> the share of low-income students in their schools than the typical
> White or Asian student. In the early 1990s, the average Latino and
> Black student attended a school where roughly a third of students were
> low-income (as measured by free and reduced-price lunch eligibility),
> but now attend schools where low income students account for nearly
> two-thirds of their classmates. There is a very strong relationship
> between the percent of Latino students in a school and the percent of
> low-income students. On a scale in which 1.0 would be a perfect
> relationship, the correlation is a high .71. The same figure is lower,
> but still high, for Black students (.53). Many minority-segregated
> schools serve both Black and Latino students. The correlation between
> the combined percentages of these underserved two groups and the
> percent of poor children is a dismaying .85.*
>
> -(Orfield et al. 2012)

The effect of "double segregation" is demonstrated previously in
California test scores, with the disparate achievement scores of
low-income students along racial/ethnic lines. Thus, we can expect that
targeting school funds and educational resources to these poverty
concentrated school districts via policy interventions like the
*concentration grant* of the LCFF will become more paramount in
addressing student inequities in educational outcomes.

## V.  Effects of funding interventions and the LCFF on student outcomes

With that understanding, policymakers have sought policy interventions
to ameliorate the inequalities and disparities in success that exist
amongst student groups. The LCFF developed and adopted by the California
state legislature takes a funding approach to address these inequities
by targeting funds to high-needs students. A meta-analysis of the
effects of differential school inputs on student outcomes found that
resource inputs of teacher education, teacher salary, pupil/teacher
ratio, and administrative inputs (which can be facilitated by increased
funding) found evidence of statistically significant relationships
between those resource inputs and student outcomes (Hedges, Laine, &
Greenwald, 1994).

With LCFF not being fully funded until 2018 (an increased K-12
commitment of \$18 billion), and the adoption of Common Core standards
in 2015 (and subsequent change in state testing from the STAR to SBAC
test), conducting a quality longitudinal analysis of LCFF's impact on
student performance has been a challenge for policy analysts. Johnson
and Tanner's 2018 study is among the first to assess LCFF's impacts on
student outcomes. In regards to the aforementioned challenges, they take
into account years of exposure and changes in testing procedures,
isolate the impact of LCFF funding increases from pre-existing trends
and other coincidental changes, and "norm" both the STAR and SBAC tests
to the National Assessment of Educational Progress (NAEP), which over
this time period, had not changed. The results of their analysis showed
average gains in mathematics and, to a smaller extent, in reading for
all students. They found effects for high school math scores are
particularly strong for students from low-income families (Johnson and
Tanner, 2018).

More specifically, Johnson and Tanner find that a \$1,000 increase in
the average per-pupil spending during 8th through 11th grades leads to a
0.19 standard deviation increase in math and a 0.08 standard deviation
increase in reading for poor children. A one standard deviation increase
in the proportion of revenue that is unrestricted is roughly 4
percentage points. The same increase leads to a 0.08 standard deviations
in reading for non-poor children, for whom no impact on math achievement
is detectable. Only 5.8% of California's public school children are
Black, so they were unable to break down the results on school-level
test scores separately for Black students due to missing reported
information in public data when small numbers of Black children are in a
school. However, they do find that among Hispanic children, a \$1,000
increase in per-pupil spending during 8th through 11th grades leads to
an increase of 0.19 standard deviations in math, and 0.11 standard
deviations in reading. No statistically significant effects were
detectable for White students. The overall positive effects evaluated in
their study increase in tandem with the amount of spending increases and
the number of school-age years of exposure (Johnson & Tanner, 2018). We
take a more simplified approach to our analysis of the *concentration
grant* by analyzing the interaction effect between the increase in
per-pupil spending that comes with the *concentration grant* and test
scores. We come up with similar results in our analysis when utilizing
this method.

One of the most glaring challenges with analyzing public school finance
is the lack of comprehensive school-level financial data, making it
difficult to determine spending *within* a district and whether the
*supplemental* and *concentration grants* are reaching the students and
schools with the highest need. As a result, analysts rely heavily on
teacher pay and experience data to evaluate whether funding is reaching
the groups that LCFF targets, but this paints a limited framework of
understanding. Nevertheless, Johnson and Tanner posit that LCFF-induced
increases when utilized for teacher salaries per pupil (which include
both increases in the number of teachers hired and increases in teacher
salary) have a positive statistically significant effect on student
achievement for low-income and Hispanic students (Johnson & Tanner,
2018). Their findings in this regard are supported by Julien Lafortune's
analysis of whether the increased funding from LCFF is reaching
high-need students. Lafortune finds that the increase in funding from
LCFF was spent on salaries and benefits for teachers and staff. Between
the 2013--14 and 2017--18 school years, student spending in high-need
districts rose by over \$500 more per pupil than in low-need districts.
Class sizes during this period decreased in high-need districts more so
than in low-need districts. Lafortune's findings for the most part
indicate that LCFF funding is reaching the high-need students for whom
it was intended. However, high-need districts have a greater reliance on
novice and less-qualified staff, suggesting it may take time for gains
from LCFF to manifest in high-need schools and districts. Lafortune
recommends that ensuring the equitable distribution of LCFF funding will
require policies that track funding within districts better, therefore
allowing for better accountability of school districts and their use of
funds for high-needs students (Lafortune, 2019).

## VI. Analysis

Our study aims to determine if the three-tiered grant structure of the
LCFF is achieving its intended purpose of funneling money equitably to
high needs students. This analysis was performed using a jupyter
notebook, which is an editor that allows the integration of the python
programming language and markdown language into a single readable
notebook. The original data sources, data cleaning merging process and
documentation, all regression models, and additional supporting
documentation for this project are available to view at
[[https://github.com/fiendskrah/finalcapstone]{.underline}](https://github.com/fiendskrah/finalcapstone).

*Data Sources*

In order to conduct our analyses, we first synthesized several datasets.
These datasets are 1) student performance data, represented by scores on
the Smarter Balanced Assessments (SBAC) in both English language arts
(ELA) and math, 2) LCFF funding by district, and 3) eligibility data for
FRPM. All data sets provide data for academic year 2018-2019, which is
the focal time period of our study. The number of districts varied
across datasets: (ELA: 921, math: 920, LCFF: 944, and FRPM: 978). All of
these data sets, with the exception of the LCFF dataset, have
school-level data, while the LCFF dataset is limited to the district
level. Because the LCFF is our primary interest, we opted to aggregate
the other datasets to the district level, which allowed us to use school
districts as our unit of analysis. Ideally, our analysis would be
performed using individual schools as units of analysis. However, as
found in previous studies, financial data that is school specific is not
readily available.

*Methods*

To answer our research question, we performed regression analyses to
determine if a district receiving a concentration grant had any effect
on a student group's scores on the SBAC tests. The SBAC data contains
scores for each of the seventeen student groups within each district,
but some student groups were missing from certain districts. A school
district could conceivably not contain enough students of a particular
group to report their scores, but this likely is indicative of at least
slightly imperfect SBAC data. As a result, the number of observations
varied from model to model depending on which student group was being
examined. The seventeen student groups are: all students, African
American, American Indian, Alaska Native, Asian, Filipino, Hispanic,
Pacific Islander, White, multiple races, English Language Learner,
English Learners only (anachronistic group indicating no additional
learning barrier such as low-income), RFP (English learners who have
achieved proficiency), English only, socioeconomically disadvantaged,
students with disabilities, foster youth, and homeless youth. Due to
redundancies in student group classifications, we chose to only examine
seven of the groups: 1) English Learner and 2) SES disadvantaged,
because they are student classifications targeted by the formula; 3)
African American, due to continuing disparities in outcomes along racial
and ethnic lines resulting from historical racism and segregation; 4)
Hispanic, for the same reasons as African American but also because of
their large share of the state's population; 5) Asian, who have the
highest statewide average scores, and 6) White, to serve as a group not
widely adversely affected by structural inequalities as their other
student peers. Additionally, we examined the 7) "all student" group to
observe any potential district-wide effect on SBAC scores.

*Dependent variables*

The SBAC data contains two potential indicators to serve as our
dependent variable: 'currstatus', or the scores for that particular
student group for the given year, or 'change', which indicates the
difference between this year\'s scores and last year\'s score. While we
built models utilizing both options, we decided to discard the models
utilizing the change variable, despite returning significant
coefficients, due to an understanding that the recency of the
implementation of Common Core curricula in academic years 2014-2015
resulted in an overall drop in performance, but scores are expected to
increase annually as teachers and students adjust to the new curricula,
standards, and new testing model. This expected increase could
potentially confound any model with the 'change' indicator as it's
dependent variable.

*Independent variables*

To distinguish districts that receive a concentration grant from those
that do not, we create a binary dummy variable called 'treatment'.
Districts where treatment = 1 are districts that have an *unduplicated
pupil count* comprising of at least 55% of the district's student body,
as determined by the LCFF data. The LCFF data contains separate columns
itemizing each of the three grants. While our interest is in the
effectiveness of the *concentration grant*, regressing only the funds
from the *concentration grant* would leave out the districts with less
than 55% of high needs students, which serve as a control group for our
analysis. To include the control group, we needed to use the total
amount of grant funding. However, district funding from all three grants
varies due to variations across districts in the number of students they
have and the number of students determined to be high-needs. Therefore,
regressing the total funding from LCFF without accounting for the size
of the district in some way would result in a wide variation, creating
too much noise in the coefficients to be interpreted meaningfully. While
the LCFF data does not contain information on enrollment numbers, the
FPRM data contains enrollment numbers by individual schools, which,
after aggregating to the district-level, can be matched to the LCFF data
districts and then divided by total funding to infer a
'per\_capita\_spending' variable. After these inferences and merges, we
have our synthesized dataset which includes district identifiers,
per-capita grants allotted to those districts, and performance
indicators of each student group in each district. We can now slice this
data by selecting student groups, which allow us to construct regression
models for each student group across the state. Our regression formula
is:

> *Performance indicator = a + per-capita funding + treatment +
> (per-capita funding x treatment) + e*

The interaction effect of (per-capita funding x treatment) allows us to
account for the size of each district while still capturing the
increased funding from the concentration grant.

**Primary Findings**

![](media/image6.png){width="6.5in" height="2.986111111111111in"}We
performed fourteen regression analyses (seven student groups x two
performance indicators) and found three statistically significant
interaction coefficients across three student groups. Table 1 displays
the regression output for our model of English scores for the English
Language Learner group. This model is of particular significance due to
the disadvantages experienced by the English Language Learner group
described in Section III. We find a very small, but statistically
significant coefficient of 0.0032 for our interaction effect, indicating
that the extra funding allotted by the concentration grant to the
treatment districts are having a positive effect on english SBAC scores
for the English Language Learner group.

![](media/image7.png){width="6.5in" height="2.9722222222222223in"}Table
2 displays the regression output for our model of math scores for the
SES disadvantaged group. This finding is also relevant to policy makers
due to LCFF's stated intention of assisting low-income students. Again,
the coefficient of 0.0023 is very small, but statistically significant,
indicating a positive effect of the *concentration grant* on the scores
of low-income students.

Lastly, table 3 presents the regression output for our model of math
scores for the Hispanic student group. An initial concern of this
finding is that there could be some overlap between student groups. A
student could conceivably belong to both the English learner group and
the Hispanic group (or the low-income group and the Hispanic group).
However, due to the larger proportion of Hispanic students in California
compared to other states, and the understanding that they perform lower
than their White and Asian peers, we include this model in our findings.

While individual ethnic groups are not targeted by the LCFF, this
finding indicates that there can be beneficial effects to groups beyond
those targeted. The 2018 LAO report cited in Section III indicates that
achievement gaps exist between ethnic groups, even when controlling for
factors understood to impact academic performance such as income.
However, the fact that we did not find significant coefficients in any
other ethnic group model urges caution when interpreting these benefits
to be widely applicable.

![](media/image8.png){width="6.5in"height="3.0416666666666665in"}
## VII. Discussion

We interpret the statistically significant large negative coefficient
for 'treatment' across each of these models to be endogenous to those
districts. The treatment districts are those districts that have a
majority (\<55%) share of high-needs students. Due to the lower
achievement scores of high-needs students, these districts are extremely
likely to have lower scores just by virtue of the composition of their
student body. Furthermore, 'assignment' of the treatment in this case is
not random due to being specifically targeted by LCFF, which violates
OLS assumptions. The large size of the 'treatment' coefficients make
sense when considering that some of these districts have *unduplicated
pupil count* shares as large as 100% and that concentrated poverty has a
negative effect on academic achievement, as described in Section III.
The 'per\_capita\_funds' variable does not encompass anything beyond the
amount of money granted to a district on a per student basis, and
includes all districts in the synthesized dataset. We therefore conclude
that neither the 'treatment' variable nor the 'per\_capita\_funding'
variable can be interpreted with much meaning by themselves.

*Limitations*

One major limitation lies in the incompleteness of the data. Each of the
datasets used in this study contained fewer districts than the 1,037
districts listed on the California Department of Education's website.
Additionally, the differences in the number of districts across our
datasets creates problems in matching districts. While it is troubling
to note that the state lacks complete data on institutions receiving
taxpayer money, the number of school districts is subject to change
based on districts being created, merged, or dissolved as a county's
need arises. This is simply indicative of the fact that data collection
and management in this area needs to be improved. It is not uncommon for
studies regarding education policy to drop districts due to matching
errors or outliers. In our case, districts are dropped in the process of
slicing student groups from the synthesized dataset based on if those
groups' scores are collected by that district.

Another limitation is the recency with which the LCFF has been fully
funded by the state legislature. As discussed in Section V, the
2018-2019 academic year is the first year that LCFF was fully funded.
While this study produced optimistic results, we will need to see more
data years of academic performance with full LCFF funding to have a
comprehensive understanding of the effects of the *concentration grant*
on student performance.

*Policy Recommendations*

As discussed in Section IV, the disadvantages associated with low-income
students is further compounded by race and ethnicity. Poor Black and
Latino students perform lower than their other low-income peers,
creating impacts of "double segregation," a phenomenon that is projected
to worsen as these students attend schools whose student body is
becoming increasingly poorer and more segregated. State legislators
should consider expanding the criteria for *concentration grants* to
include extra funding to students affected by double segregation. One
way to address this could be to create another funding layer to the LCFF; in the same way that the *concentration grant* targets high-needs
students, a fourth *'double segregation'* grant could trigger under
certain conditions that would allow it to target high-needs districts
with high Black and Latino populations.

The issues with incompleteness and inconsistency in education data
hamper the efforts of policy analysts to improve California's education
systems, including both the current study and several studies in our
literature review. The California Department of Education should perform
a full review of data collection methods and storage practices to ensure
the completeness and accuracy of data for future studies. The previously
cited differences in district numbers between datasets (and the lack of
explanation or notation from CDE) are glaring examples. Other issues
include the use of 14-digit CDS (county, district, school) codes, which
are designed to make matching operations between datasets easier.
However, in practice, the CDS codes are constructed differently across
datasets: some datasets contain one column with the entire CDS code,
while others split the code into three columns (one for county,
district, and school, respectively). CDS codes are particularly
important when one needs to distinguish between districts or schools
that have the same name. Finally, as described in Section V, the
complete inaccessibility of school level financial data hampers policy
analyst's ability to determine whether funds are actually being directed
to high need students and schools within a district. Requiring funding
reporting at the individual school level would allow for a more thorough
analysis of the impact and implementation of the formula, as well as
facilitate better school district accountability and transparency.

While the incompleteness of data could be indicative of a lack of
systematic oversight in data control, the issue of inconsistency could
potentially be addressed by the development of an application
programming interface (API). APIs allow any user who has acquired
approval to interface directly with the agency's data via a coding
language to download only requested data in a format specified by the
user. APIs are common at companies that make data available for users,
but are increasingly being used at federal agencies such as the Bureau
for Economic Analysis to allow for transparency and accountability. If
CDE were to develop an API, it could potentially facilitate more precise
analysis of education policy. Generally speaking, all local and federal
government agencies that deal with public-facing data should work
towards developing an API. Ideally, there would be national guidance
from congress in terms of storage practices to allow better comparison
of data across states.

*Items for further research*

As alluded to in the previous section, this analysis relies on only one
data year of full funding for the LCFF. Further iterations of this study
as data years become available could yield a more complete understanding
of the dynamics of concentration funding on high-needs school districts.
Another dimension to this iteration could be differentiation of district
types. According to CDE's website, there are 345 unified school
districts, 528 elementary school districts, 76 high school districts,
and 88 'other' districts, each with a different base grant formulation,
as discussed in Section II. Differentiating models by district type
could reveal varying effects of the *concentration grant.*

An alternate iteration of this research could be to incorporate
regression discontinuity designs. The sample of districts could be
narrowed down and 'paired' for treatment and control in a number of
ways. Scholars can utilize geographic data, income data, and demographic
data from the census to match districts that are most alike in household
income, ethnic group makeup, or are within a certain distance from each
other to better isolate the effects of the *concentration grant.*

Importantly, the major barrier to understanding the link between funding
and student performance, as discussed throughout this report, is the
lack of comprehensive school-level funding data. We have relatively good
school-level data for performance indicators and FRPM eligibility, but
without untangling the complex web of funding mechanisms that power
individual schools, policy makers will always lack a complete
understanding of the impacts of increased funding on academic outcomes.

# Conclusion

This study contributes to the collective body of research of policy
makers and education policy scholars by examining the link between
increased per-capita funding via the LCFF *concentration grant* and
academic performance for disadvantaged student groups. Our findings
indicate that LCFF is having a beneficial effect for these student
groups, but we emphasize that incomplete data continues to be a major
impediment to a comprehensive understanding of these effects. Moreover,
LCFF is still in its infancy: more years of being fully funded,
increased length of exposure to LCFF, and allowing time for students and
teachers to adjust to new curricula and testing is crucial to
understanding the full effects of this policy. Unfortunately, due to the
volatility of California's revenue base due to a heavy reliance on
personal income taxes, funding LCFF stands to be impacted by dramatic
fluctuations in the economy, such as the economic recession we are
currently experiencing due to COVID-19. Nevertheless, LCFF is a
groundbreaking policy intervention that very early on is showing
promising returns. Further analyses of the formula stand to assist the
state with adjusting the formula for better optimization, and informing
school finance reform efforts in other states.

# Works Cited

Martin, I. (2006). Does school finance litigation cause taxpayer revolt?
Serrano and Proposition 13. *Law & Society Review*, *40*(3), 525-558.

*Serrano v. Priest*, 487 P.2d 1241, 5 Cal. 3d 584, 96 Cal. Rptr. 601
(1971).

LaFortune, J. (2019). School Resources and the Local Control Funding
Formula: Is Increased Spending Reaching High-Need Students? Technical
Appendices. *Public Policy Institute of California*.

Taylor, M. (2013). An overview of the local control funding formula.
*Legislative Analyst's Office Sacramento, CA.*

Murphy, P., & Paluch, J. (2018). Financing California's Public Schools.
*Public Policy Institute of California*.

Hill, L., & Ugo, I. (2015). Implementing California\'s School Funding
Formula: Will High-Need Students Benefit? Technical Appendix. *Public
Policy Institute of California*

Taylor, M. (2018). The 2018-19 budget: Proposition 98 education
analysis. *Legislative Analyst\'s Office Sacramento, CA.*

Coleman, J. S., Campbell, E. Q., Hobson, C., McPartland, J., Mood, A.
M., Weinfeld, F. D., & York, R. L. (1966). Equality of Educational
Opportunity. *Washington, DC, US Department of Health, Education, and
Welfare, Office of Education, US Government Printing Office*

Bradbury, B., Corak, M., Waldfogel, J., & Washbrook, E. (2015). *Too
many children left behind: The US achievement gap in comparative
perspective*. Russell Sage Foundation.

Newburger, H. B., Birch, E. L., & Wachter, S. M. (Eds.). (2011).
*Neighborhood and life chances: How place matters in modern America*.
University of Pennsylvania Press.

Wallin, R. (2012). The Great Divergence: America's Growing Inequality
Crisis and What We Can Do About It. *Library Journal*, *137*(7), 88.

Rothstein, R. (2004). A wider lens on the black-white achievement gap.
*Phi Delta Kappan*, *86*(2), 104-110.

Rumberger, R. W., & Palardy, G. J. (2005). Does segregation still
matter? The impact of student composition on academic achievement in
high school. *Teachers college record*, *107*(9), 1999.

Hedges, L. V., Laine, R. D., & Greenwald, R. (1994). An exchange: Part
I: Does money matter? A meta-analysis of studies of the effects of
differential school inputs on student outcomes. *Educational
researcher*, *23*(3), 5-14.

Orfield, G., Kucsera, J., & Siegel-Hawley, G. (2012). E pluribus\...
separation: Deepening double segregation for more students.

Johnson, R. C., & Tanner, S. (2018). Money and Freedom: The Impact of
California\'s School Finance Reform on Academic Achievement and the
Composition of District Spending. Technical Report. Getting Down to
Facts II. *Policy Analysis for California Education, PACE*.
