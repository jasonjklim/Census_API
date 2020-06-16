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

ET variable name | Original Variable name | Original Variable Description
-- | -- | --
Fips_State | STATE | State FIPS CODE
Fips_Place | PLACE | Place FIPS CODE
Fips_State_Place | None | None
City_Name | NAME | City Name
St_Name | STNAME | State Name
NYU_500_Largest | Calculated | None
Year | YEAR | Year of estimate
Pop_Total | P0010001 | Total population from ACS Survey
Per_15to44_years(%) | Calculated |  
Per_18_years_and_over(%) | Calculated |  
Per_65_years_and_over(%) | Calculated |  
Pop_Male | P0050001 | Estimate!!Total!!Male
Pop_Female | P0050002 | Estimate Total Female
Pop_White | Calculated |  
Pop_Black | Calculated |  
Pop_Asian | Calculated |  
Pop_AIAN | Calculated |  
Pop_NHOPI | Calculated |  
Pop_Nonhispanic | P0090001 | Estimate!!Total!!Not Hispanic or Latino
Pop_Hispanic | P0080001 | Estimate!!Total!!Hispanic or Latino

