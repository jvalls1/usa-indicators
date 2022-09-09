## Energy

All Information about energy is located at https://www.eia.com

## Energy Production 

To follow all path of energy production we are going to use this infographics <br>

![Energy Infographic](energy_chart.webp)

Credits of graphic <br>
*LLNL April, 2018. Data is based on DOE/EIA MER (2017). If this information or reproduction is used, credit must be given to the Lawrence Livermore National Laboratory and the department of Energy. under whose auspices the work was performed. This chart was revised in 2017 to reflec changes made in mid-2016 to the Energy Information Administration's analysis methodology and reporting*

### Files

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

## Energy Retail Prices

### Files

All files are obtained following the same pattern as above section, a json file is downloaded.
https://api.eia.gov/series/?api_key=YOUR_KEY&series_id=SERIE_ID<br>
XX is the state code and A or M annual or montly periodicity.

|Serie ID |Description |Units| 
|---------|------------|-----|
|MGACD.XX.A|Motor gasoline price in the transportation sector |Dollars per million Btu|
|MGCCD.XX.A|Motor gasoline price in the commercial sector     |Dollars per million Btu|
|MGICD.XX.A|Motor gasoline price in the industrial sector     |Dollars per million Btu|
|          |                                                  |                       |
|NGACD.XX.A|Natural gas price in the transportation sector    |Dollars per million Btu|
|NGCCD.XX.A|Natural gas price in the commercial sector        |Dollars per million Btu|
|NGICD.XX.A|Natural gas price in the industrial sector	      |Dollars per million Btu|
|NGRCD.XX.A|Natural gas price in the residential sector	      |Dollars per million Btu|
|          |                                                  |                       |
|ESACD.XX.A|Electricity price in the transportation sector    |Dollars per million Btu|
|ESCCD.XX.A|Electricity price in the commercial sector	      |Dollars per million Btu|
|ESICD.XX.A|Electricity price in the industrial sector	      |Dollars per million Btu|
|ESRCD.XX.A|Electricity price in the residential sector	      |Dollars per million Btu|

There are other series but for now it is enough to illustrate the state of energy.

### Fields

All series return a JSON file with the following structure:
{request:
	{command: "series",
	 seriees_id: "SEDS.SOTGP.CA.A"},
 series:
 0: {
     series_id: "SEDS.SOTGP.CA.A",
     name: "Solar thermal and photovoltaic electricity total net generation, California",
     units: "Million kilowatthours",
     f: "A",
     description: "Solar thermal and photov…notes and documentation.",
     
 }
 















