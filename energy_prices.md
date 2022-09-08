## Energy

All Information about energy is located at https://www.eia.com

### Energy Production

To follow all path of energy production we are going to use this infographics <br>

![Energy Infographic](energy_chart.webp)

Credits of graphic <br>
*LLNL April, 2018. Data is based on DOE/EIA MER (2017). If this information or reproduction is used, credit must be given to the Lawrence Livermore National Laboratory and the department of Energy. under whose auspices the work was performed. This chart was revised in 2017 to reflec changes made in mid-2016 to the Energy Information Administration's analysis methodology and reporting*

#### Solar thermal and photovoltaic electricity total net generation 
Series SOTGP. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.SOTGP.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Nuclear electricity total net generation
Series NUETP. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.NUETP.XX.A <br>
Where XX is state code. A stands for annual <br>
	
#### Hydroelectricity net generation in the electric power sector <br>
Series HYEGP. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.HYEGP.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Wind electricity total net generation
Series WYTCP. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.WYTCP.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Geothermal electricity net generation in the electric power sector
Series GEEGP. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.GEEGP.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Natural Gas Production
The url's for obtaining the files are:<br>
Natural Gas Gross Withdrawals and Production. Units Montly-Million Cubic Feet.<br> 
https://www.eia.gov/dnav/ng/ng_prod_sum_a_EPG0_FGW_mmcf_m.htm <br>
Natural Marketed Production. Units Montly-Million Cubic Feet. <br>
https://www.eia.gov/dnav/ng/ng_prod_sum_a_EPG0_VGM_mmcf_m.htm <br>

#### Coal
Series CLPRB. Coal Production. Units Billion Btu
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.CLPRB.XX.A <br>
Series CLPRP. Coal Production. Thousand of short Tons.
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.CLPRP.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Biomass total consumption
Series BMTCB. <br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.BMTCB.XX.A <br>
Where XX is state code. A stands for annual <br>

#### Petroleum
Series PATCB. All petroleum products total consumption. Billion Btu.
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.PATCB.XX.A <br>
Series PATCP. All petroleum products total production. Thousand of barrels
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SEDS.PATCP.XX.A <br>

#### Electricity Generation
Electricity generation is calculated adding all primary energy sources: solar, nuclear, hidro, wind, geothermal, natural gas,coal.
The url for obtaining the file is:<br>
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=ELEC.GEN.ALL-XX-99.M<br>
Where XX is the state code and M the periodicity. <br> 



### Energy Retail Prices

### Origin of data
The origin of data comes from EIA (Energy Information Administration)<br>
[EIA](https://www.eia.gov)<br>
https://www.eia.gov<vr>
  
Datasets:
  * [Electricity Sales to Ultime Consumers](https://www.eia.gov/opendata/browser/electricity/retail-sales)
  
### Files

* Electricity  
We must use an API.
  * URL: https://api.eia.gov/v2/electricity/retail-sales/data/
  * Method: GET
  * Description: Electricity sales to ultimate customer by state and sector (number of customers, average price, revenue, and megawatthours of sales). 
    Sources: Forms EIA-826, EIA-861, EIA-861M
  
* Natural Gas Prices
  We must use an API.
  * URL: https//www.eia.gov/opendata/browser/natural-gas/pri/sum)
  * Method: GET

* 
