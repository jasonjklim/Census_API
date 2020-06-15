# Census API PULL for PLACE(CITY FIPS CODE) 



* The American Community Survey (ACS) helps local officials, community leaders, and businesses understand the changes taking place in their communities. It is the premier source for detailed population and housing information about our nation. 
During analysis, from 509 cities of NYU dataset, 495/ 496 cities are covered by ACS1. Most of cities are covered by ACS1 for NYU City Health Dataset. 
<br>





## When to Use 1-year, 3-year, or 5-year Estimates of ACS
Choosing which dataset involves more than simply considering the population size in your area. You must think about the balance between currency and sample size/reliability/precision. The following is the chart that is helped to decide which ACS dataset to use.

1-year   estimates | 3-year   estimates* | 5-year estimates
-- | -- | --
12   months of collected data Example: 2018 ACS 1-year estimates Date   collected between: January 1, 2018 and | 36 months of collected   data Example: 2011-2013   ACS 3-year estimates Date collected between: January 1, 2011 and | 60 months of collected data Example: 2014-2018 ACS 5-year estimates Date collected between: January   1, 2014 and
Data   for areas with populations of 65,000+ | Data for areas with   populations of 20,000+ | Data for all areas



## Column Description (Data Dictionary)
 These are general variables that I want to use for further research.<br>
 Data Dictionary of final data products will show the orginal variables for Census and calculations if any.



ET   variable name | Original Variable Description
-- | --
fips_state | State FIPS CODE
fips_place | Place FIPS CODE
fips_state_place | None
city_name | City Name
st_name | State Name
NYU_500_Largest | None
year | Year of estimate
census_population | Total population from ACS Survey
15 to 44 years | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!15 to 44   years
18 years and over | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!18 years   and over
65 years and over | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!65 years   and over
pop_male | Estimate!!Total!!Male
pop_female | Estimate Total Female
pop_white | Estimate!!Total!!White alone
pop_black | Estimate!!Total!!Black or African American alone
pop_asian | Estimate!!Total!!Asian alone
pop_AIAN | Estimate!!Total!!American Indian and Alaska Native alone
pop_NHOPI | Estimate!!Total!!Native Hawaiian and Other Pacific Islander alone
pop_nonhispanic | Estimate!!Total!!Not Hispanic or Latino
pop_hispanic | Estimate!!Total!!Hispanic or Latino

