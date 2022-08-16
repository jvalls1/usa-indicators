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
We are only going to use by State and by City files. 

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
Records that contains info about United States: 149,484  <br> 
<br>

Samples:

``GlobalLandTemperaturesByState.csv:1743-11-01,10.722000000000001,2.898,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1743-12-01,,,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-01-01,,,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-02-01,,,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-03-01,,,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-04-01,19.075,2.902,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-05-01,21.197,2.844,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-06-01,25.29,2.879,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-07-01,26.42,2.841,Alabama,United States``<br>
``GlobalLandTemperaturesByState.csv:1744-08-01,,,Alabama,United States``<br>


<br>

* Global Land Temperatures By City (GlobalLandTemperaturesByCity.csv)<br>

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

``1820-01-01,2.1010000000000004,3.217,Abilene,United States,32.95N,100.53W``<br>
``1820-02-01,6.926,2.853,Abilene,United States,32.95N,100.53W``<br>
``1820-03-01,10.767,2.395,Abilene,United States,32.95N,100.53W``<br>
``1820-04-01,17.988999999999994,2.202,Abilene,United States,32.95N,100.53W``<br>
``1820-05-01,21.809,2.036,Abilene,United States,32.95N,100.53W``<br>
``1820-06-01,25.682,2.008,Abilene,United States,32.95N,100.53W``<br>
``1820-07-01,26.268,1.8019999999999998,Abilene,United States,32.95N,100.53W``<br>
``1820-08-01,25.048,1.895,Abilene,United States,32.95N,100.53W``<br>
``1820-09-01,22.435,2.2159999999999997,Abilene,United States,32.95N,100.53W``<br>
``1820-10-01,15.83,2.169,Abilene,United States,32.95N,100.53W``<br>



Total number of records: 8,599,213 <br>
Records that contains info about United States Cities: 687,289 


