# preemption_entrepreneurship
The data in this repository consists of the inputs to our preemption and entrepreneurship project, funded by the Kauffman Foundation. The data allowed us to explore a state's propensity to preempt as well as the impact of that preemption on entrepreneurial outcomes

## About the Data
The data here are broken up into four main bucekts: 1) preemption data; 2) state government data; 3) Kauffman data; and, 4) business and demographic data. 

All data was collected from other sources, which are cited below. Some data were extrapolated, based on available data and to fill in years. Each bucket below includes a short description, codebook, and sources.

### Preemption data
The preemption data consists of seven policy domains that we determined impacted entrepreneurial outcomes. 

#### Codebook
Variable	Description

state:	State

year:	Year

minwage:	Minimum Wage preemption implementation year and all subsequent years

minwageimplementation:	Year of minimum wage preemption implementation

paidleave:	Paid Leave preemption implementation year and all subsequent years

paidleaveimplementation:	Year of paid leave preemption implementation

ridesharing:	Ride Sharing preemption implementation year and all subsequent years

ridesharingimplementation:	Year of Ride Sharing preemption implementation

projectlaboragreement:	Project Labor Agreement preemption implementation year and all subsequent years

projectlaboragreementimplementation:	Year of Project Labor Agreement preemption implementation

fairscheduling:	Fair Scheduling preemption implementation year and all subsequent years

fairschedulingimplementation:	Year of Fair Scheduling preemption implementation

prevailingwage:	Prevailing Wage preemption implementation year and all subsequent years

prevailingwageimplementation:	Year of Prevailing Wage preemption implementation

broadband:	Municipal Broadband preemption implementation year and all subsequent years

broadbandimplementation:	Year of municipal broadband preemption implementation

#### Sources
Economic Policy Institute. "Worker Rights Preemption in the U.S.: A Map of the Campaign to Suppress Worker Rights in the States." Aug. 2019. Web. 09 Nov. 2020.

Institute for Local Self-Reliance. "Community Network Map." Community Broadband Networks. Jan. 2020. Web. 09 Nov. 2020.

Orms, Maria Elizabeth., and David Reed. States with Restrictions to Municipal Broadband Deployments and the Effects of the Restriction. Thesis. University of Colorado, 2013. 2013. Print.

### State government data
This data represents the partisan makeup of each state government as well as measures of legislative professionalism. 

#### Codebook
Variable	Description

state:	State

year:	Year

governorcontrol:	Party Control of Governorship (0=Republican, 1=Democratic)

senatecontrol:	Party Control of State Senate (0=Republican, 1=Democratic)

housecontrol:	Party Control of State house (0=Republican, 1=Democratic)

unifiedchamber:	Unified Party Control of Chambers (0=Not unified, 1=Unified)

unifiedgovernment:	Unified Party Control of Governorship and Chambers (0=Not unified, 1=Unified)

session.length:	Number of days the legislature is in session in each year

legislatorsalary:	Dollar amount of a legislator's salary per year

#### Sources
Williams, Ben. "State Partisan Composition." State Partisan Composition. 2020. Web. 09 Nov. 2020. <https://www.ncsl.org/research/about-state-legislatures/partisan-composition.aspx>.

Saucedo, Selena. "2020 State Legislative Session Calendar." 2020 State Legislative Session Calendar. 2020. Web. 09 Nov. 2020. <https://www.ncsl.org/research/about-state-legislatures/2020-state-legislative-session-calendar.aspx>.

Zoch, Mandy. "2018 Legislator Compensation Information." 2018 Legislator Compensation Information. 2018. Web. 09 Nov. 2020. <https://www.ncsl.org/research/about-state-legislatures/legislator-compensation-2018.aspx>.

### Kauffman Indicators data
The Kauffman Indicators were used to measure entrepreneurial outcomes. 

#### Codebook
Variable	Description

state:	State

year:	Year

startup.job.creation..average...of.jobs.created.:	Average number of new startup jobs per 1,000 people

startup.early.survival.rate..percent.:	Percentage of startups still in business after more than one year

opportunity.share.of.new.entrepreneaurs..percent.:	Percentage of entrepreneurs that started new businesses out of opportunity as opposed ot necessity

rate.of.new.entrepreneurs..percent.:	Percetnage of adults that become new entreprenuers in an average month, out of 100,000 adults

#### Sources
Kauffman Foundation. "Early-Stage Entrepreneurship: Kauffman Indicators." Kauffman Indicators of Entrepreneurship. Web. 09 Nov. 2020. <https://indicators.kauffman.org/series/earlystage>.

### Business & Demographic Data
This data was used for control variables and to measure other entrepreneurial outcomes. 

#### Codebook
Variable	Description

state:	State

year: Year

estabs_entry_rate:	The number of new establishments divided by the average number of establishments, times 100

estabs_exit_rate:	The number of establishments that exited divided by the average number of establishments, times 100

job_creation_rate:	Rate of jobs created

job_destruction_rate:	Rate of jobs lost

agricultureemploymentpercent:	Percent of employees in the Agriculture sector

retailemploymentpercent:	Percent of employees in the Retail sector

artsemploymentpercent:	Percent of employees in the Arts sector

unemploymentpercent:	Percent of individuals unemployed

nonwhitepercent:	Percent of people that are non-white

bachelors.percent:	Percent of people that have at least a Bachelor's Degree

#### Sources
U.S. Census Bureau. "Business Dynamics Statistics (BDS)." The United States Census Bureau. 17 Sept. 2020. Web. 09 Nov. 2020.

US Census Bureau. "American Community Survey (ACS)." The United States Census Bureau. 22 Oct. 2020. Web. 09 Nov. 2020. <https://www.census.gov/programs-surveys/acs/>.
