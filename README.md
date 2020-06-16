# Census Data for Cities (PLACE FIPS CODE)



## Purpose 
This is Census data of U.S. major cities from 1990-2018 using API. The purpose of data is to compare U.S. major city populations over different periods. In these periods, we choose 4 categories to look closer, which are: 
- Sex - male, female
- General Age Groups- 15-44 years, 18 years or older, 65 years or older
- Race - White, Black, Asian, American Indian and Alaska Native, Native Hawaiian and Other Pacific Islander 
- Ethnicity - Hispanic, nonhispanic

Using these datasets, we may find out the population details in U.S. major cities. 

## General Info
* In the dataset, we could see NYU_500_largest. NYU dataset means cities that are belonged to NYU City Health Dashboard. City Health Dashboard launched in 2018 with data on over 35 measures of health and drivers of health for the 500 largest U.S. cities. So, NYU_500_largest variable will show whether the city belongs to City Health Dashboard or not. 
https://www.cityhealthdashboard.com/. <br>
For Our API and data cleaning for City Health Dashboard, it is located on the following address:<br>
https://github.com/kschnippel/Reference_Place/tree/master/City%20Health%20Dataset<br> During analysis, from 509 cities of NYU dataset, 495/ 496 cities are covered by ACS1. Most of cities are covered by ACS1 for NYU City Health Dataset. 
* The American Community Survey (ACS) is an ongoing survey that provides vital information on a yearly basis about our nation and its people. The American Community Survey (ACS) helps local officials, community leaders, and businesses understand the changes taking place in their communities. It is the premier source for detailed population and housing information about our nation. <br>

* Single-year and multiyear estimates from the ACS are
all “period” estimates derived from a sample collected
over a period of time, as opposed to “point-in-time”
estimates such as those from past decennial censuses. While an ACS 1-year estimate includes information collected over a 12-month period, an ACS 5-year estimate
includes data collected over a 60-month period. Multiyear estimates require some considerations that
single-year estimates do not. For example, multiyear
estimates released in consecutive years consist mostly
of overlapping years and shared data.

<br>





## When to Use 1-year, 3-year, or 5-year Estimates of ACS
Choosing which dataset involves more than simply considering the population size in your area. You must think about the balance between currency and sample size/reliability/precision. The following is the chart that is helped to decide which ACS dataset to use.

1-year   estimates | 3-year   estimates* | 5-year estimates
-- | -- | --
12   months of collected data Example: 2018 ACS 1-year estimates Date   collected between: January 1, 2018 and | 36 months of collected   data Example: 2011-2013   ACS 3-year estimates Date collected between: January 1, 2011 and | 60 months of collected data Example: 2014-2018 ACS 5-year estimates Date collected between: January   1, 2014 and
Data   for areas with populations of 65,000+ | Data for areas with   populations of 20,000+ | Data for all areas

**In this project, I decided to use ACS 1-year estimates because we want to compare the population of U.S. major cities.**

## Column Description (Data Dictionary)
These are general variable names and its meanings <br>
 * Data Dictionary of final data products will show the original variables for Census and calculations if any. Data Dictionary is located in the year folders and it's named **'_dict'** at the end. 
 * If there is a calculation of different fields, then I created 'grouping' file to know which variables from Census API are used and how it is calculated. For example, when Age groups are not in Census API and calculate with the summation of different age groups, then "Age_grouping_YYYY.csv" when helps to find out variables and its calculation.
 


ET variable name | Original Variable Description
-- | --
Fips_State | State FIPS CODE
Fips_Place | Place FIPS CODE
Fips_State_Place | None
City_Name | City Name
St_Name | State Name
NYU_500_Largest | None
Year | Year of estimate
Pop_Total | Total population from ACS Survey
Per_15to44_years(%) | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!15 to 44   years
Per_18_years_and_over(%) | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!18 years   and over
Per_65_years_and_over(%) | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!65 years   and over
Pop_Male | Estimate!!Total!!Male
Pop_Female | Estimate Total Female
Pop_White | Estimate!!Total!!White alone
Pop_Black | Estimate!!Total!!Black or African American alone
Pop_Asian | Estimate!!Total!!Asian alone
Pop_AIAN | Estimate!!Total!!American Indian and Alaska Native alone
Pop_NHOPI | Estimate!!Total!!Native Hawaiian and Other Pacific Islander alone
Pop_Nonhispanic | Estimate!!Total!!Not Hispanic or Latino
Pop_Hispanic | Estimate!!Total!!Hispanic or Latino

