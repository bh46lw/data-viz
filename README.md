Project Title
The trend of male & female working population in Hong Kong and their participation rate between 2011 & 2016 

Prerequisites
This project will assist Hong Kong Labour Force Department's junior officials to build its own dashboard by using Tableau Public.  First thing is, to download the living population, working population, participation rate and usual working hours per week from https://data.gov.hk (that is, open data from HK) for data cleansing and re-organization before import into Tableau for further drafting the visualization.  A spatial file is also required to downloaded from open source to find Hong Kong map for presentation purpose.
Last, it is required to download the Tableau Public by registering an account for 1 year free license for running this assignment.

Files will be as follow:
2011 Census data
https://www.census2011.gov.hk/en/district-profiles.html
Choose Main Tables and select demographic characteristic for living population by sex by district.  Then select economic characteristic for working population by sex by district and median income by sex by district.
2016 Census data
https://www.bycensus2016.gov.hk/en/bc-dp.html
Choose demographic characteristic for living population by sex by district.  Then select economic characteristic for working population by sex by district, median income by sex by district and usual working hours per week by sex by district.

Spatial file for HK administration areas
http://www.diva-gis.org/gdata. 
This file gives the longitude and latitude of drawing HK map by district.

All data loading in each dashboard will first select the xlsx files from 2011 & 2016 data sets into Tableau software.  Then merge the dataset by adding the connection with the file in the same dashboard.  For those need to use spatial file for Map distribution presentation, we need to load the spatial file in that dashbaord (for example, in first output in below link).  Each dashbaord will be selected different presentation format to present the living population (first output) growth rate, then second ouput will mainly overview working population and the median income.  Third Output will be used to display median income and occupation by sex penetration for presentation.  So that when Audiecne review the visualization, they can easily to visualize and compare the growth rate or penetration rate by each sex for their attention.

Difficulties: Due to data download from HK open source, some of the information shown in the excel files have been formatted.  It is not a raw data, in order to load in the Tableau, it is required to re-format it without any formula or formatting before loading in the Tableua. 

# data-viz
1) Overall all dashboard built for this project (including all prototypes we used to let the viewer to develop its output)
https://public.tableau.com/profile/teresa2429#!/

First Output - Living Population by District by Sex (2011 vs 2016) - Final
Metadata:	
Map - Male Living Population by District (2011 vs 2016)
Map - Female Living Population By District (2011 vs 2016)
2011 vs 2016 Male Living Population By Districts
2011 vs 2016 Female Living Population By Districts
2011 vs 2016 Male Living Population Growth Rate by District
2011 vs 2016 Female Living Population by District Growth Rate
https://public.tableau.com/profile/teresa2429#!/vizhome/LivingPopulationbyDistrictbySex2011vs2016-Final/Map-Malepopulation

Second Output - 2011 vs 2016 Working Population with Median Income by District by Sex - Final
Metadata:	
2011 & 2016 participation rate by sex by district
2011 vs 2016 Working Population by Sex by District
2011 & 2016 Median Income by Sex by District
2011 vs 2016 Median Income Growth Rate by Sex by District
https://public.tableau.com/profile/teresa2429#!/vizhome/2011vs2016WorkingPopulationwithMedianIncomeBydistrictbySex-Final/20112016participationratebysexbydistrict

Third Output - 2011 vs 2016 Median Income by Sex by District - Final
Metadata:	
2011 vs 2016 Median Income Growth Rate by Sex by District
2011 vs 2016 Male Median Income by District
2011 vs 2016 Female Median Income by District
2011 vs 2016 Median Income by Sex by District
2016 Working Population by Occupation for Male
2016 Working Population by Occupation for Female
2016 Occupation by Sex by District
https://public.tableau.com/profile/teresa2429#!/vizhome/2016OccupationbySexbyDistrict/2011vs2016Medianincomegrowthrate


