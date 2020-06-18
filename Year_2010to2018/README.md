# Year 2010-2018 Census Population Data for U.S. Major Cities

This folder is for the Year 2010-2018  Census population data for U.S. Major cities that I combined all API pulls from different years.
<Br>
 The documentation of variable choices and any calculation formulas are located in the following issue:
https://github.com/kschnippel/Reference_Place/issues/4

**Divided 2010-2018 files into two csv files (2010-2014 and 2015-2018) because 2010-2018 file was too large, so Github preview function is not working**

## Source

ACS 1 year estimates of each year have the same cities. In the initial API pulls 2018, ACS1, which contains data for areas with populations of 65,000+, has 630 cities.

I will pull two API data from Census

* ACS1 (Sex, Race, Ethnicity)
* ACS1/subject (Age group)


Year | Source
-- | --
2010 | https://api.census.gov/data/2010/acs/acs1<br>     https://api.census.gov/data/2010/acs/acs1/subject
2011 | https://api.census.gov/data/2011/acs/acs1  <br>   https://api.census.gov/data/2011/acs/acs1/subject
2012 | https://api.census.gov/data/2012/acs/acs1 <br>    https://api.census.gov/data/2012/acs/acs1/subject
2013 | https://api.census.gov/data/2013/acs/acs1  <br>   https://api.census.gov/data/2013/acs/acs1/subject
2014 | https://api.census.gov/data/2014/acs/acs1 <br>    https://api.census.gov/data/2014/acs/acs1/subject
2015 | https://api.census.gov/data/2015/acs/acs1  <br>   https://api.census.gov/data/2015/acs/acs1/subject
2016 | https://api.census.gov/data/2016/acs/acs1   <br>  https://api.census.gov/data/2016/acs/acs1/subject
2017 | https://api.census.gov/data/2017/acs/acs1 <br>    https://api.census.gov/data/2017/acs/acs1/subject
2018 | https://api.census.gov/data/2018/acs/acs1  <br>   https://api.census.gov/data/2018/acs/acs1/subject



## Column Description

The following chart is Everytown variables and original variables that I pulled from Census ACS.

<br>






ET   variable name | Original Variable name | Original Variable Description
-- | -- | --
FIPS_STATE | STATE | State FIPS CODE
FIPS_PLACE | PLACE | Place FIPS CODE
FIPS_STATE_PLACE | None | None
CITY_NAME | NAME | City Name
ST_NAME | STNAME | State Name
NYU_500_LARGEST | Calculated | None
YEAR | YEAR | Year of estimate
POP_TOTAL | B01001_001E | Total Persons,Population Subjects
PER_AGE_15TO44 | S0101_C01_023E, S0101_C02_024E | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!15 to 44   years
PER_AGE_18PLUS | S0101_C01_025E, S0101_C02_026E | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!18 years   and over
PER_AGE_65PLUS | S0101_C01_028E, S0101_C02_030E | Estimate!!Percent!!Total population!!SELECTED AGE CATEGORIES!!65 years   and over
POP_MALE | B01001_002E | Estimate!!Total!!Male
POP_FEMALE | B01001_026E | Estimate Total Female
POP_WHITE | B02001_002E | Estimate!!Total!!White alone
POP_BLACK | B02001_003E | Estimate!!Total!!Black or African American alone
POP_ASIAN | B02001_005E | Estimate!!Total!!Asian alone
POP_AIAN | B02001_004E | Estimate!!Total!!American Indian and Alaska Native alone
POP_NHOPI | B02001_006E | Estimate!!Total!!Native Hawaiian and Other Pacific Islander alone
POP_NONHISPANIC | B03003_002E | Estimate!!Total!!Not Hispanic or Latino
POP_HISPANIC | B03003_003E | Estimate!!Total!!Hispanic or Latino


