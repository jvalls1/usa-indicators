# Us-indicators
Data Engineering Project to research the United States of America quality of life. 

The main objective of project is to gather data for meseauring and giving insights 
of quality of live evolution in US.

## List of data/indicators:

* [Inmigration data](immigration_data.md)
* [Population](population.md)
* [School level](school_level.md)
* [Land Temperature](land_temperature.md)
* [Air quality](air_quality.md) 
* [Traffic Trends](traffic_trends.md)
* Health<br>
  * [Diabetes Prevalence](diabetes.md)
* [Life expectancy](life_expectation.md)
* [Heath insurance](health_insurance.md)
* [Causes of death](causes_of_death.md)
* [Energy](energy.md)
* Economic Activity
  * [Hardvard Complexity Index](complexity_index.md)
* Housing 
  * [Buying prices](buying_prices.md) 
  * [Rental prices](rental_prices.md)
* Personal Economy
  * [Per Capita Personal Income](per_capita_personal_income.md)
  * [Unemployment](unemployment.md)
* Indicators
  * [CPI (Cosumer Prices Index)](cpi.md)
  * [Average Prices](average_prices.md) 


## Description of files that contains all datasets 
   * [Files](files.md)
  
## Data Quality and Assessment

[This section describes the data quality process](quality.md)<br> 
For each section of data a profiling data process is executed and then based on the results <br>
it is run a cleaning process. As a result of both process a buch of new datasets are generated.<br>

## Air Quality

* There are 14 files for each one corresponding to a substance. 
* The structure of these files are the same. 
* A field with two letters identifying the state are missing. For example '01' -> 'AL'. It can be generate easily in the 
  next stage of the pipeline. No change to original data was made. 
* There are no measures for every county. States have at last one point of observation.


## Traffic Trends

* Traffic_trends.ipnyb, is used for profiling and cleaning. The file 
* Traffic_trends.py runs for all file sets  


## Health Insurance

*  Health_insurance_profiling.ipynb, is used for profiling and cleaning. The file sahie2019.csv is used.
*  Health_insurance_profiling.py runs for all sets of files sahieXXXX.csv. 
   A file is generate form each source file:
   * Source: XXXX_sahie_county.csv > Generated: cl_XXX_sahie_country.csv
   
The following data are missing for each XXXX_sahie_county

* State: Hawai
* County: Kalawao County
* Facts: NIPR,nipr_moe,NUI,nui_moe,NIC,nic_moe,PCTUI,pctui_moe,PCTIC,pctic_moe,PCTELIG,pctelig_moe,PCTLIIC,pctliic_moe


## Causes of death

* causes_of_death.ipynb, is used for profiling and cleaning.
* causes_of_death.py, runs for the two files.

Permanent file: 2014-2019. <br>
Provisional file: 2020-2021, COVID info included. <br>

Actions taken: <br>
The two data files are joined in one file. <br>
The provisional file has 35 colums and the permanent one 30. <br>
4 Columns from provisional corresponds are for reflecting COVID deaths. <br>
1 Column from provisional is date of update. <br>
1 Column from provisional will be dropped. <br>
4 Columns form permanent will be added. <br>

Names of columns are too large. It may be difficult to treat them for coding.
The name of columns will be renamed as follows.

| New Column name | Old Column name |
| ----------------| --------------- |
| state_name      | Jurisdiction of Occurrence |                                                                        
| year            | MMWR Year       |                                                                                          
| week            | MMWR Week       |                                                                                   
| week_end_date   | Week Ending Date |
| flag_provisional| ----      |
| allcause        | All Cause |                                                                                          
| natcause        | Natural Cause |                                                                                      
| sept            | Septicemia (A40-A41) |                                                                               
| neopl           | Malignant neoplasms (C00-C97) |                                                                      
| diab            | Diabetes mellitus (E10-E14) |
| alz             | Alzheimer disease (G30) |                                                                            
| inflpn          | Influenza and pneumonia (J09-J18) |                                                                  
| clrd            | Chronic lower respiratory diseases (J40-J47) |                                                       
| otherresp       | Other diseases of respiratory system (J00-J06,J30-J39,J67,J70-J98) |                                 
| nephr           | Nephritis, nephrotic syndrome and nephrosis (N00-N07,N17-N19,N25-N27) |                              
| otherunk        | Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified (R00-R99)|
| hd              | Diseases of heart (I00-I09,I11,I13,I20-I51) |                                                       
| stroke          | Cerebrovascular diseases (I60-I69)|                                                                 
| cov19mcod       | COVID-19 (U071, Multiple Cause of Death) |                                                           
| cov19ucod       | COVID-19 (U071, Underlying Cause of Death) |    
| flag_allcause   | flag_allcause |                                                                                     
| flag_natcause   | flag_natcause |                                                                                      
| flag_sept       | flag_sept |                                                                                           
| flag_neopl      | flag_neopl |                                                                                   
| flag_diab       | flag_diab |                                                                                          
| flag_alz        | flag_alz |                                                                                            
| flag_inflpn     | flag_inflpn |                                                                                        
| flag_clrd       | flag_clrd |                                                                                             
| flag_otherresp  | flag_otherresp |                                                                                    
| flag_nephr      | flag_nephr |                                                                                         
| flag_otherunk   | flag_otherunk |                                                                                      
| flag_hd         | flag_hd |                                                                                             
| flag_stroke     | flag_stroke |                                                                                         
| flag_cov19mcod  | flag_cov19mcod |                                                                                   
| flag_cov19ucod  | flag_cov19ucod |     

All fields that begins with 'flag_' must have values 0 or 1 <br>
,, -> 0 <br>
Other info -> 1 <br>

## Housing
### Buying Prices

### Rental Prices
   
## Personal Economy

### Per Capita Personal Income

* PCPI_profiling.ipynb, is used for profiling and cleaning. 
* PCPI_profiling.py runs for all set of files. 

### Unemployment

* unemployment.ipynb, is used for profiling and cleaning. 
* unemployment.py runs for all set of files. 
77 Counties belonging to Puerto Rico has no data<br>


# Data Model 

Considerations.

 1/ Census Bureau midyear population estimates. Estimates for 2010-2020 reflect county population estimates available as of March 2021. These population estimates are based on the 2010 census. BEA will incorporate Census Bureau midyear population estimates based on the 2020 census results when they become available.
2/ Per capita personal income was computed using Census Bureau midyear population estimates. Estimates for 2010-2020 reflect county population estimates available as of March 2021. These estimates are based on the 2010 census. BEA will incorporate Census Bureau midyear population estimates based on the 2020 census results when they become available.
* Estimates for 1979 forward reflect Alaska Census Areas as defined by the Census Bureau; those for prior years reflect Alaska Census Divisions as defined in the 1970 Decennial Census.
* Estimates from 1988 forward separate Aleutian Islands Census Area (02010) into Aleutians East Borough (02013) and Aleutians West Census Area (02016).
* Estimates for 1991 forward separate Denali Borough (02068) from Yukon-Koyukuk Census Area (02290) and Lake and Peninsula Borough (02164) from Dillingham Census Area (02070).
* Estimates from 1993 forward separate Skagway-Yakutat-Angoon Census Area (02231) into Skagway-Hoonah-Angoon Census Area (02232) and Yakutat City and Borough (02282). Estimates from 2008 forward separate Skagway-Hoonah-Angoon Census Area (02232) into Skagway Municipality (02230) and Hoonah-Angoon Census Area (02105). Estimates from 2009 forward separate Wrangell-Petersburg Census Area (02280) into Petersburg Census Area and Wrangell City and Borough (02275). In addition, a part of the Prince of Wales-Outer Ketchikan Census Area (02201) was annexed by Ketchikan Gateway Borough (02130) and part (Meyers Chuck Area) was included in the new Wrangell City and Borough (02275). The remainder of the Prince of Wales-Outer Ketchikan Census Area (02201) was renamed Prince of Wales-Hyder Census Area (02198). Petersburg Borough (02195) was created from part of former Petersburg Census Area and part of Hoonah-Angoon Census Area (02105) for 2013 forward. Prince of Wales-Hyder Census Area (02198) added part of the former Petersburg Census Area beginning in 2013. For years 2009-2012, Petersburg Borough (02195) reflects the geographic boundaries of the former Petersburg Census Area.
* Wade Hampton Census Area was renamed Kusilvak Census Area (02158) on July 1, 2015.
* On January 2, 2019, two new county equivalents were created from the former Valdez-Cordova Census Area, Alaska (02261): Chugach Census Area (02063) and Copper River Census Area (02066). Estimates for 2020 forward reflect these changes.
* La Paz County, AZ was separated from Yuma County on January 1, 1983. The Yuma, AZ MSA contains the area that became La Paz County, AZ through 1982 and excludes it beginning with 1983.
* Broomfield County, CO, was created from parts of Adams, Boulder, Jefferson, and Weld counties effective November 15, 2001. Estimates for Broomfield county begin with 2002.
* Kalawao County, Hawaii is combined with Maui County. Separate estimates for the jurisdictions making up the combination areas are not available.
* Cibola, NM was separated from Valencia in June 1981, but in these estimates, Valencia includes Cibola through the end of 1981.
* Shannon County, SD was renamed to Oglala Lakota County, SD on May 1, 2015.
* Virginia combination areas consist of one or two independent cities with 1980 populations of less than 100,000 combined with an adjacent county. The county name appears first, followed by the city name(s). Separate estimates for the jurisdictions making up the combination area are not available. Bedford County, VA includes the independent city of Bedford for all years.
* Shawano, WI and Menominee, WI are combined as Shawano (incl. Menominee), WI for the years prior to 1989.
Metropolitan Areas are defined (geographically delineated) by the Office of Management and Budget (OMB) bulletin no. 20-01 issued March 6, 2020.
Note. All dollar estimates are in thousands of current dollars (not adjusted for inflation). Statistics presented in thousands of dollars do not indicate more precision than statistics presented in millions of dollars.
(NA) Not available.
Last updated: November 16, 2021-- new statistics for 2020; revised statistics for 1998-2019. 


     
## Maps
https://medium.com/@jl_ruiz/plot-maps-from-the-us-census-bureau-using-geopandas-and-contextily-in-python-df787647ef77
https://www.python-graph-gallery.com/choropleth-map-geopandas-python
