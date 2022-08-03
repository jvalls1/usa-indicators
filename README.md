# usa-indicators
Data Engineering Project to show the United States of America quality of life. 

The main objective of project is to gather data for meseauring and giving insights 
of quality of live evolution in USA.

List of data/indicators:

* [Inmigration data](immigration_data.md)
* [Population](population.md)
* [School level](school_level.md)
* [Land Temperature](land_temperature.md)
* [Air quality](air_quality.md) 
* [Traffic Trends](traffic_trends.md)
* [Life expectancy](life_expectation.md)
* [Heath insurance](health_insurance.md)
* [Causes of death](causes_of_death.md)
* Energy
  * [Production](production.md)
  * [Prices](energy_prices.md)
* Economic Activity
  * [Organization of Economic Complexity OEC](organization_economic_complexity.md) 
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

# resume of datasets.

* Immigration Data, State, City or Town, Year. 1 Parquet File. Aprox 3,000,000 Rows
  * part-00013-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy, 
  * part-00012-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00011-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00010-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00009-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00008-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00007-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00006-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00005-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00004-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00003-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00002-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
  * part-00001-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* Population by County, Single Ages, Races: White, Black, Other. 1960-2020. <br> 
  * us.1969_2020.singleages.adjusted.exe.gz, 238.8 MB, 6510147 Rows <br>
* Population by County, Single Ages, Extended Races. 1990-2020 <br>    
  * us.1990_2020.singleages.adjusted.exe.gz, 246.3 MB, 65160149 Rows <br>
* Land Temperature
  * GlobalLandTemperaturesByState.csv <30.49MB,   645676 Records / 149484 Records US>  
  * GlobalLandTemperaturesByCity.csv  <520.43MB, 8599213 Records / 687289 Records of US Cites>
* Air quality
  * Criteria Gases OZONE(44201),SO2(42401),CO(42101),NO2(42602), Daily,Local Level.
    * daily_44201_XXXX.zip (XXXX (1980-2020), csv, 4MB, 390000 Rows Each File)
    * daily_44401_XXXX.zip (XXXX (1980-2020), csv, 3MB, 320000 Rows Each File)
    * daily_42101_XXXX.zip (XXXX (1980-2020), csv, 2MB, 220000 Rows Each File)
    * daily_42601_XXXX.zip (XXXX (1980-2020), csv, 1.7MB, 130000 Rows Each File)
  * Particulates FRM/FEM Mass (88101)
    * daily_88101_XXXX.zip (XXXX (2005-2020), csv, Apox 6MB,      500000 Rows Aprox Each File)
  * Particulates PM2.5 non FRM/FEM Mass (88502)
    * daily_88502_XXXX.zip (XXXX (2005-2020), csv, Apox 2MB,      200000 Rows Aprox Each File)
  * Particulates PM10 Mass (81102)
    * daily_81102_XXXX.zip (XXXX (2005-2020), csv, Aprox 1.2MB,   150000 Rows Aprox Each File) 
  * Particulates PMc Mass (86101)
    * daily_86101_XXXX.zip (XXXX (2005-2020), csv, Aprox 0.5MB,    50000 Rows Aprox Each File)
  * Particulates PM2.5 Speciation
    * daily_SPEC_XXXX.zip  (XXXX (2005-2020), csv, Aprox 14MB,   2000000 Rows Aprox Each File)
  * Particulates PM10 Speciation
    * daily_PM10SPEC_XXXX.zip (XXXX (2005-2020), csv, Aprox 3MB,  250000 Rows Aprox Each File)
  * Toxics (HAPS), Precursors (VOCs,NONOxNOy), and Lead
    * daily_HAPS_XXXX.zip (XXXX (1980-2020), csv, Aprox 3MB,  250000 Rows Aprox Each File)
    * daily_VOCS_XXXX.zip (XXXX (1980-2020), csv, Aprox 6MB,  500000 Rows Aprox Each File)
    * daily_NONOxNOy_XXXX.zip (XXXX (1980-2020), csv, Aprox 4MB,  400000 Rows Aprox Each File)
    * daily_LEAD_XXXX.zip (XXXX (1980-2020), csv, Aprox 0.125MB,  15000 Rows Aprox Each File)
* Traffic Trends
    * yymmmtvt.xlxs (Where yy (year), mmm (mounth), 245 Files, 0.3MB Excel, 40000 Total Rows Aprox)
* Health Insurrance
    * sahie-XXXX-csv.zip (XXXX (2008-2019)), (csv files, 12 Files, 300000 x 12 = 3600000 Total Rows Aprox)
* Causes of Death
    * Weekly_Counts_of_Deaths_by_State_and_Select_Causes__2014-2019.json (JSON file, 2.38MB, 16500 Rows)
    * NCHS_-_Leading_Causes_of_Death__United_States.json (JSON file, 0.84MB, 7079 Rows)
* Economic Activity, Hardvard Complexity Index
    * 'What did United States of America export in YYYY.csv', ((1995-2019) 1225 Rows per file => 29400 Rows)
    * 'Where did United States of America export to in YYYY.csv', ((1995-2019) 220 Rows per file => 5280 Rows)
    * 'What did United States of America import in YYYY.csv', ((1995-2019) 1225 Rows per file => 29400 Rows)
    * 'Where did United States of America import from in YYYY,csv', ((1995-2019) 220 Rows per file => 5280 Rows)    
 * Housing
    *  Buying prices
       * County_zhvi_uc_sfrcondo_tier_0.0_0.33_sm_sa_month.csv (csv 4.7 MB)  
       * County_zhvi_uc_sfr_tier_0.33_0.67_sm_sa_month.csv (csv 4.8 MB)
       * County_zhvi_uc_condo_tier_0.33_0.67_sm_sa_month.csv  (csv 2.0 MB) 
       * County_zhvi_bdrmcnt_1_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv (csv 2.8 MB)
       * County_zhvi_bdrmcnt_2_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv (csv 4.4 MB)
       * County_zhvi_bdrmcnt_3_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv (csv 4.8 MB)
       * County_zhvi_bdrmcnt_4_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv (csv 4.7 MB)
       * County_zhvi_bdrmcnt_2_uc_sfrcondo_tier_0.33_0.67_sm_sa_month.csv (csv 3.7 MB) 
    * Renting prices
       * Zip_ZORI_AllHomesPlusMultifamily_Smoothed.csv (csv XX MB, 246738  Facts)
       * Metro_invt_fs_uc_sfrcondo_sm_month.csv (56 KB, 49572 Facts)
       
 * Personal Economy
   * Per Capita Personal Income
     * XXXX_PCI.csv (csv where XXXX stands for (1969-2020), 9425 Rows per file x 54 Years = 508950 Rows, 0.625MB per file)    
   * Unemployment
     * laucntyXX.txt => (txt where XX is year (1990-2021), 3217 Counties per filex x 32 Years = 102944 Rows + 2 Files)    
 * Indicators
   * CPI (Consumer Price Index)
     * cu.data.0.Current			       -  All current year-to-date 
     * cu.data.1.AllItems		       -  All items (item_code AA0, SA0)
     * cu.data.2.Summaries		       -  Summaries (item_code SA0, SAF,SAH, SAA, SAT, SAM, SAR, SAE, SAG,SAS, SAC)
     * cu.data.3.AsizeNorthEast		 -  A-Size areas in Northeast (area_code A1 ...)
     * cu.data.4.AsizeNorthCentral	 -  A-size areas in North Central (area_code A2 ...)
     * cu.data.5.AsizeSouth			   -  A-Size areas in South (area_code A3 ...)
     * cu.data.6.AsizeWest			     -  A-Size areas in West (area_code A4 ...)
     * cu.data.7.OtherNorthEast		 -  All other Northeast(area_code 01, X1, D1)
     * cu.data.8.OtherNorthCentral	 -  All other North Central(area_code 02, X2, D2)
     * cu.data.9.OtherSouth			   -  All other in South (area_code 03, X3, D3)
     * cu.data.10.OtherWest			   -  All other in West (area_code 04, X4)  
     * cu.data.11.USFoodBeverage		 -  All US Food and Beverage (area_code 0000, item_code SAF, SEF)    
     * cu.data.12.USHousing			   -  All US Housing (area_code 0000, item_code SAH, SEH)
     * cu.data.13.USApparel			   -  All US Apparel (area_code 0000,item_code SAA, SEA)
     * cu.data.14.USTransportation	 -  All US Transportation (area_code 0000, item_code SAT, SET)
     * cu.data.15.USMedical			   -  All US Medical (area_code 0000, item_code SAM, SEM, SS57)
     * cu.data.16.USRecreation			 -  All US Recreation (area_code 0000,item_code SAR, SER, SS31, SS61, SS62)
     * cu.data.17.USEducationAndCommunication	-  All US Education and Communication (area_code 0000, item_code SAE,SEE, SS27)
     * cu.data.18.USOtherGoodsAndServices	-  All US Other Goods and Services (area_code 0000, item_code SAG, SEG; SS33)
     * cu.data.19.PopulationSize		-  All Population-size (area_code A000, X000, D000)
     * cu.data.20.USCommoditiesServicesSpecial	-  All US Commodity and Services and Special(area_code 0000, item_code SA0, SAC, SAN, SAS)
     * cu.area					            -  Area codes		mapping file
     * cu.contacts				          -  Contacts for cu survey 
     * cu.footnote				          -  Footnote codes	mapping file
     * cu.item					            -  Item codes		mapping file
     * cu.MapErrors (TBR)			    -  Map error codes	mapping file
     * cu.period				            -  Period codes 	mapping file
     * cu.series				            -  All series and their beginning and end dates
     * cu.txt					            -  General information

   * Averages Prices
     * ap.data.0.Current		- All current year-to-date data
     *	ap.data.1.HouseholdFuels	- All household fuels data
     *	ap.data.2.Gasoline		- All gasoline data
     *	ap.data.3.Food			- All food data
     * ap.area				- Area codes		mapping file
     * ap.contacts			- Contacts for ap survey  
     * ap.footnote			- Footnote codes	mapping file
     * ap.item				- Item codes		mapping file
     * ap.period			- Period codes		mapping file
     * ap.series			- All series and their beginning and end Dates
     * ap.txt				- General information

 ## Directory structure and location.
 
 The structure of directory where data will be loacated is:

 /-- data<br> 
      &nbsp;&nbsp;| -- immigration_data <br>
      &nbsp;&nbsp;| -- population <br>
      &nbsp;&nbsp;| -- school_level <br>
      &nbsp;&nbsp;| -- land_temperature <br>
      &nbsp;&nbsp;| -- air_quality <br>
      &nbsp;&nbsp;| -- traffic_trends <br>
      &nbsp;&nbsp;| -- life_expectancy <br>
      &nbsp;&nbsp;| -- health_insurrance <br>
      &nbsp;&nbsp;| -- causes_of_death <br>
      &nbsp;&nbsp;| -- energy <br>
      &nbsp;&nbsp;| -- economic_activity <br>
      &nbsp;&nbsp;| -- housing <br>
      &nbsp;&nbsp;| -- personal_economy <br>
      &nbsp;&nbsp;| -- indicators <br>
      &nbsp;&nbsp;| -- geographies <br>

Locations:<br>
* Due the large number and volume of files a google drive is used

# Data Quality

This section describes the data quality process.<br> 
For each section of data a profiling data process is executed and then based on the results <br>
it is run a cleaning process. As a result of both process a buch of new datasets are generated.<br>

## Health Insurance

*  Health_insurance_profiling.ipynb, is used for profiling and cleaning. The file sahie2019.csv is used.
*  Health_insurance_profiling.py runs for all set of files sahieXXXX.csv. 
   A file is generate form each source file:
   * Source: XXXX_sahie_county.csv > Generated: cl_XXX_sahie_country.csv
   
The following data are missing for each XXXX_sahie_county

* State: Hawai
* County: Kalawao County
* Facts: NIPR,nipr_moe,NUI,nui_moe,NIC,nic_moe,PCTUI,pctui_moe,PCTIC,pctic_moe,PCTELIG,pctelig_moe,PCTLIIC,pctliic_moe
   
## Personal Economy

### Per Capita Personal Income

* PCPI_profiling.ipynb, is used for profiling and cleaning. 
* PCPI_profiling.py runs for all set of files. 


### Unemployment
     
## Maps
https://medium.com/@jl_ruiz/plot-maps-from-the-us-census-bureau-using-geopandas-and-contextily-in-python-df787647ef77
https://www.python-graph-gallery.com/choropleth-map-geopandas-python
