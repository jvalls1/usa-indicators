## Traffic Trends

Data origin:

[Office of Highway Policy Information](https://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm)<br>
https://www.fhwa.dot.gov/policyinformation/travel_monitoring/tvt.cfm

#### Files

Available files to download. <br>
Monthly data => From 2002-01 to 2022-05 => 245 Files <br>
Format => Excel Files *.xlxs <br>
Naming conventions : yymmtvt.xlxs, example: 20juntvt.xlxs

Each excel file, has a group of sheets, we select:

* Page 4: Changes on Rural Arteries By Region and State
* Page 5: Changes on Urban Arterial Roads by Region and State
* Page 6: Changes on ALL Estimates Roads by Region and State

#### Fields

A script is built to translate Sheet formats into a row format:

Fields of row format (CSV Files)

***Year:*** Year of data <br>
***Month:*** Month <br>
***State-Code:*** US 2 digit state Code <br>
***Vehicle-Miles-Pre:*** Vehicles Miles in millions, preliminary data <br>
***Vehicle-Miles-Pre-A-YearAgo:*** Vehicles Miles in millions, preliminary data, last yeart, same month <br> 
***Percentatge-Change:*** Percentantge change respect to same month of previous year  
***Vehicle-Miles-Rev:*** Vehicles Miles in millions, revised data of previous month <br>
***Vehicle-Miles-Rev-A-YearAgo:*** Vehicles Miles in millions, revised data of previois month of previous year. <br>
***Percentatge-Change-Rev:*** Percentatge change on revised data. 




