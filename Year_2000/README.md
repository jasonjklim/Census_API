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



ET variable name | Original Variable name | Original Variable Description
-- | -- | --
Fips_State | State (FIPS) | State (FIPS)
Fips_Place | PLACE | Place FIPS CODE
Fips_State_Place | None | None
City_Name | NAME | City Name
St_Name | NAME | State Name
NYU_500_Largest | Calculated | None
Year |   |  
Pop_Total | P001001 | Population:Total
Per_15to44_years(%) | Calculated | None
Per_18_years_and_over(%) | P005001 | RACE 18+:Total
Per_65_years_and_over(%) | Calculated | None
Pop_Male | P012002 | SEX BY AGE:Total Male
Pop_Female | P012026 | SEX BY AGE:Total Female
Pop_White | P007002 | RACE:White alone
Pop_Black | P007003 | RACE:Bl/AfAm alone
Pop_Asian | P007005 | RACE:Asian alone
Pop_AIAN | P007004 | RACE:AmInd/AK alone
Pop_NHOPI | P007006 | RACE:HI alone
Pop_Nonhispanic | P004003 | HISPANIC:Total notHispanic or Latino
Pop_Hispanic | P004002 | HISPANIC:Total Hispanic or Latino

