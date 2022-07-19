## Average Prices

### Origin of data:
[Bureau of Labor Statistics](https://www.bls.gov/cpi/tables/home.htm)<br>
https://www.bls.gov/cpi/tables/home.htm <br>

The bureau of labor statistics offers historical data of large sets: <br>
[LABSTATS](https://download.bls.gov/pub/time.series/)<br>
https://download.bls.gov/pub/time.series/<br>

### Files
Files of average prices are under ap directory: <br>

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

### Relationships of files

![Average_Files](average_prices.svg)

External dimensions: <br>
 * SEASONAL
 * ITEM
 * AREA
 * PERIOD
 * PERIODICITY <br>
 
Main dimension: <br>
 * SERIE

Facts: <br>
 * rest of tables.

### Number of Rows

| Files | Number of Rows | Fact Table | Dimension Table |
|-------|----------------|------------|-----------------|
| ap.data.0.Current | 189048 | Yes | No | 
| ap.data.1.HouseholdFuels | 103139 | Yes  | No |
| ap.data.2.Gasoline | 88754 | Yes | No |
| ap.data.3.Food | 139987 | Yes | No |
| ap.area	 | 75 | No | Yes |
| ap.item | 165 | No | Yes |
| ap.period	 | 14 | No | Yes |
| ap.series| 1485 | No | Yes |
