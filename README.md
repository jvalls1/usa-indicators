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

  


## Maps
https://medium.com/@jl_ruiz/plot-maps-from-the-us-census-bureau-using-geopandas-and-contextily-in-python-df787647ef77
https://www.python-graph-gallery.com/choropleth-map-geopandas-python
