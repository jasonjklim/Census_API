# Year 2005-2009 Census Population Data for U.S. Major Cities

This folder is for the Year 2005-2009  Census population data for U.S. Major cities that I combined all API pulls from different years.
<Br>
 The documentation of variable choices and any calculation formulas are located in the following issue:
https://github.com/kschnippel/Reference_Place/issues/5


## Source

ACS1/subject is started in 2010. On the other hand, Census ACS1 started in 2005. So, I pulled the dasta from the oldest ACS1. <br>


Year | Source
-- | --
2005 | https://api.census.gov/data/2005/acs/acs1
2006 | https://api.census.gov/data/2006/acs/acs1
2007 | https://api.census.gov/data/2007/acs/acs1
2008 | https://api.census.gov/data/2008/acs/acs1
2009 | https://api.census.gov/data/2009/acs/acs1

## Column Description

The following chart is Everytown variables and original variables that I pulled from Census ACS.<br>
**Since there is no ACS1/subject table, Age group will be calculated by combining the age and sex variables from ACS1.<br>
For age grouping, please use Age_grouping_2005to2009.csv for your reference.**

<br>



ET variable name | Original Variable name | Original Variable Description
-- | -- | --
FIPS_STATE | STATE | State FIPS CODE
FIPS_PLACE | PLACE | Place FIPS CODE
FIPS_STATE_PLACE | None | None
CITY_NAME | NAME | City Name
ST_NAME | STNAME | State Name
NYU_500_LARGEST | Calculated | None
YEAR | YEAR | Year of estimate
POP_TOTAL | B01001_001E | Total population from ACS Survey
PER_AGE_15TO44 | Calculated | None
PER_AGE_18PLUS | Calculated | None
PER_AGE_65PLUS | Calculated | None
POP_MALE | B01001_002E | Estimate!!Total!!Male
POP_FEMALE | B01001_026E | Estimate Total Female
POP_WHITE | B02001_002E | Estimate!!Total!!White alone
POP_BLACK | B02001_003E | Estimate!!Total!!Black or African American alone
POP_ASIAN | B02001_005E | Estimate!!Total!!Asian alone
POP_AIAN | B02001_004E | Estimate!!Total!!American Indian and Alaska Native alone
POP_NHOPI | B02001_006E | Estimate!!Total!!Native Hawaiian and Other Pacific Islander alone
POP_NONHISPANIC | C03001_002E, B03003_002E | Estimate!!Total!!Not Hispanic or Latino
POP_HISPANIC | C03001_003E, B03003_003E | Estimate!!Total!!Hispanic or Latino



