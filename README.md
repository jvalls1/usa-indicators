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
    

## Maps
https://medium.com/@jl_ruiz/plot-maps-from-the-us-census-bureau-using-geopandas-and-contextily-in-python-df787647ef77
https://www.python-graph-gallery.com/choropleth-map-geopandas-python
