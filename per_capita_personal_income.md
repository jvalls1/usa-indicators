## Per Capita Personal Income

### Origin of Data.

Bureau of Economic Analysis and Commerce.<br>
[BEA](https://www.bea.gov/)<br>
https://www.bea.gov/

To Download data: <br>
https://apps.bea.gov/itable/iTable.cfm?ReqID=70&step=1 <br>
CAINC1 Personal Income Summary: Personal Income, Population, Per Capita Personal Income

### Files

It can be chosen series by year and all counties.
Each file can be renamed to yyyy_pcpi.csv
Files donloaded:
* 2022_PCPI.csv
* 2021_PCPI.csv
* 2020_PCPI.csv
* ....
* 1969_PCPI.csv

### Rows per file.
9425 Rows per file, containing 3 distinct facs per County
~ 54 Years x 9425 = 508950 Rows 

### Fields 

***GeoFips***: Code of Fips entity <br>
***GeoName***: Name of Geographic Entity <br>
***LineCode***: Posible values (1,2,3) <br>
***Description***: Description of the fact. 
  * Population (persons) 
  * Personal income (thousands of dollars)
  * Per capita personal income (dollars)<br>

***Value***: Number (Integer), representing value in Dollars.

We must add a year at the end of each row, to concatenate all files

### Data Preview

|GeoFips|GeoName|LineCode|Description|2020|
|-------|-------|--------|-----------|----|
|01001|Autauga|AL|1 Personal income (thousands of dollars)|2628375|
|01001|Autauga|AL|2 Population (persons)|56145|
|01001|Autauga|AL|3 Per capita personal income (dollars)|46814|
|01003|Baldwin|AL|1 Personal income (thousands of dollars)|11682821|
|01003|Baldwin|AL|2 Population (persons)|229287|
|01003|Baldwin|AL|3 Per capita personal income (dollars)|50953|
|01005|Barbour|AL|1 Personal income (thousands of dollars)|930687|
|01005|Barbour|AL|2 Population (persons)|24589|
|01005|Barbour|AL|3 Per capita personal income (dollars)|37850|
|01007|Bibb|AL|1 Personal income (thousands of dollars)|759270|
|01007|Bibb|AL|2 Population (persons)|22136|
|01007|Bibb|AL|3 Per capita personal income (dollars)|34300|
|01009|Blount|AL|1 Personal income (thousands of dollars)|2246150|
|01009|Blount|AL|2 Population (persons)|57879|















