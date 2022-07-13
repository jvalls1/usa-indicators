## Land Temperature

#### Source of data.

[Land Surface Temperature](https://www.kaggle.com/code/daverosenman/climate-change-land-temperature-data-1850-2015/data)<br>
https://www.kaggle.com/code/daverosenman/climate-change-land-temperature-data-1850-2015/data

Usability => 7.5/10 <br>
License => [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) <br>
Expected Update Frequency => Not specified

#### Files:

* Global Average Land Temperature by Country (GlobalLandTemperaturesByCountry.csv)
* Global Average Land Temperature by State (GlobalLandTemperaturesByState.csv)
* Global Land Temperatures By Major City (GlobalLandTemperaturesByMajorCity.csv)
* Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)

#### Fields:
We are onlygoing to use by State and by City files. 

* Global Average Land Temperature by State (GlobalLandTemperaturesByState.csv)

<table>
  <theader>
    <th>name</th>
    <th>description</th>
    <th>type</th>
  </theader> 
  <tbody>
    <tr><td>dt</td><td>date</td><td>date in format dd/MM/YYYY</td></tr>
    <tr><td>#AverageTemperature</td><td>Avarage temperature for this day and terrritory</td><td>Decimal</td></tr>
    <tr><td>#AverageTemperatureUncertainty</td><td>Max Error to fit in 95%</td><td>Decimal</td></tr>
    <tr><td>State</td><td>State</td><td>String</td></tr>
    <tr><td>Country</td><td>Country</td><td>String</td></tr>
  </tbody>
</table>

Total number of records: 645,676 <br>
Records that contains info about United States States: 149,484  <br> 
<br>

Samples:




<br>
* Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)

<table>
  <theader>
    <th>name</th>
    <th>description</th>
    <th>type</th>
  </theader> 
  <tbody>
    <tr><td>dt</td><td>date</td><td>date in format dd/MM/YYYY</td></tr>
    <tr><td>#AverageTemperature</td><td>Avarage temperature for this day and terrritory</td><td>Decimal</td></tr>
    <tr><td>#AverageTemperatureUncertainty</td><td>Max Error to fit in 95%</td><td>Decimal</td></tr>
    <tr><td>City</td><td>City</td><td>String</td></tr>
    <tr><td>Country</td><td>Country</td><td>String</td></tr>
    <tr><td>Longitude</td><td>Longitude</td><td>String</td></tr>
    <tr><td>Latitude</td><td>Latitude</td><td>String</td></tr>
  </tbody>
</table>
<br>

Samples:




Total number of records: 8,599,213 <br>
Records that contains info about United States Cities: 687,289 


