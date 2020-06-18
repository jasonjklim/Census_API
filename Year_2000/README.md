# Year 2000 Census Population Data for U.S. Major Cities

This folder is for the Year 2000 Census population data for U.S. Major cities that I combined all API pulls from different years.
<Br>
 The documentation of variable choices and any calculation formulas are located in the following issue:
https://github.com/kschnippel/Reference_Place/issues/6#issue-635727978


## Source
For the Year 2000, 2000 Decennial: Summary File 1 Dataset may give us the variable that we can use it. <br>
https://api.census.gov/data/2000/sf1/variables.html

## Column Description

The following chart is Everytown variables and original variables that I pulled from Census ACS.

**Age group will be calculated by combining the age and sex variables from SF1.
For age grouping, please use Age_grouping_2000.csv for your reference.**

<br>




ET   variable name | Original Variable name | Original Variable Description
-- | -- | --
FIPS_STATE | State (FIPS) | State (FIPS)
FIPS_PLACE | PLACE | Place FIPS CODE
FIPS_STATE_PLACE | None | None
CITY_NAME | NAME | City Name
ST_NAME | NAME | State Name
NYU_500_LARGEST | Calculated | None
YEAR |   |  
POP_TOTAL | P001001 | Population:Total
PER_AGE_15TO44 | Calculated | None
PER_AGE_18PLUS | P005001 | RACE 18+:Total
PER_AGE_65PLUS | Calculated | None
POP_MALE | P012002 | SEX BY AGE:Total Male
POP_FEMALE | P012026 | SEX BY AGE:Total Female
POP_WHITE | P007002 | RACE:White alone
POP_BLACK | P007003 | RACE:Bl/AfAm alone
POP_ASIAN | P007005 | RACE:Asian alone
POP_AIAN | P007004 | RACE:AmInd/AK alone
POP_NHOPI | P007006 | RACE:HI alone
POP_NONHISPANIC | P004003 | HISPANIC:Total notHispanic or Latino
POP_HISPANIC | P004002 | HISPANIC:Total Hispanic or Latino

