# Year 1990 Census Population Data for U.S. Major Cities

This folder is for the Year 1990 Census population data for U.S. Major cities that I combined all API pulls from different years.
<Br>
 The documentation of variable choices and any calculation formulas are located in the following issue:
https://github.com/kschnippel/Reference_Place/issues/6#issuecomment-642939136


## Source
For the Year 1990, 1990 Decennial Census of Population and Housing - Summary File 1: Summary File 1 Dataset may give us the variable that we can use it.

https://api.census.gov/data/1990/sf1/variables.html

## Column Description

The following chart is Everytown variables and original variables that I pulled from Census ACS.

<br>

**Age group will be calculated by combining the age and sex variables from SF1. For age grouping, please use Age_grouping_1990.csv for your reference.**
<br>

**Race group will be calculated by combining the different race variables from SF1. For race grouping, please use Race_grouping_1990.csv for your reference.** 
<Br>



ET   variable name | Original Variable name | Original Variable Description
-- | -- | --
FIPS_STATE | STATE | State FIPS CODE
FIPS_PLACE | PLACE | Place FIPS CODE
FIPS_STATE_PLACE | None | None
CITY_NAME | NAME | City Name
ST_NAME | STNAME | State Name
NYU_500_LARGEST | Calculated | None
YEAR | YEAR | Year of estimate
POP_TOTAL | P0010001 | Total Persons,Population Subjects
PER_AGE_15TO44 | Calculated
PER_AGE_18PLUS | Calculated
PER_AGE_65PLUS | Calculated
POP_MALE | P0050001 | Estimate!!Total!!Male
POP_FEMALE | P0050002 | Estimate Total Female
POP_WHITE | Calculated
POP_BLACK | Calculated
POP_ASIAN | Calculated
POP_AIAN | Calculated
POP_NHOPI | Calculated
POP_NONHISPANIC | P0090001 | Estimate!!Total!!Not Hispanic or Latino
POP_HISPANIC | P0080001 | Estimate!!Total!!Hispanic or Latino




