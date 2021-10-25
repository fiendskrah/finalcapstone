# finalcapstone

## Data sources

CDE - LCFF

### California statewide summary data for the Local Control Funding Formula (LCFF)
**Parsing and cleaning LCFF data file** 
 > which numbers to use?
reporting and distribution figures for school funds change throughout the year as new information becomes known by local administrators, [on the CDE website](https://www.cde.ca.gov/fg/aa/pa/).

Because of this, we want to base our analysis on the versions of the figures that represent the entirety of the data year.

>The Annual Apportionment, certified by February 20 in the following year, is based on annual data that LEAs report to CDE. After the Annual Apportionment certification, which supersedes the P-2 calculations, Annual is recertified three times, known as Annual R1, R2, and R3, with LEAs reporting corrected data at specific times. Any data corrections are reflected with the subsequent years’ certifications.


[from the CDE website](https://www.cde.ca.gov/fg/aa/pa/)

see also the [faq page for lcff](https://www.cde.ca.gov/fg/aa/lc/lcfffaq.asp)

The LCFF snapshot contains districts AND schools. Filter the school code variable to '0' to select only districts. 

Effectively there are a bunch of extra funding streams that are derrived from cases where a school district or charter school was going to see egregious budget cuts due to the new funding system (lcff). The original analysis used only the three major funding streams, but there are additional questions like 
    
- what share of the total funds distributed do these extra streams represent? 
- LCFF is beyond it's transitionary period, are those extra funding streams still functioning? 
    - If so, are they necessary? effective? 
    
### Select data year

he LCFF was phased in as a policy to allow for a smoother transition. Additonal funds were alloted to allow school districts time to make changes that comport with the new funding formula. This transitionary period ended with data year **2018-19*** representing the first fully funded LCFF data year. 


# new PPIC report
[edsource.com article](https://edsource.org/2021/nearly-half-of-money-for-high-needs-students-not-getting-to-their-schools-analysis-finds/662405)
[full report](https://edsource.org/2021/nearly-half-of-money-for-high-needs-students-not-getting-to-their-schools-analysis-finds/662405)
school instead of by district, ensuring that the money would go to students who generated the extra funding. The challenge with the latter is that it might encourage further segregation — redrawing school boundaries to include larger concentrations of low-income families, Lafortune said.