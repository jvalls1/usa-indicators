## Rental Prices

### Origin of Data

Rental Prices are taken from Zillow HomePage.<br>
[Rental Prices](https://www.zillow.com/research/data/)<br>
https://www.zillow.com/research/data/<br>

From their web page:

```RENTALS```

```Zillow Observed Rent Index (ZORI): A smoothed measure of the typical observed market rate rent across a given region. ZORI is a repeat-rent index that is weighted to the rental housing stock to ensure representativeness across the entire market, not just those homes currently listed for-rent. The index is dollar-denominated by computing the mean of listed rents that fall into the 40th to 60th percentile range for all homes and apartments in a given region, which is once again weighted to reflect the rental housing stock. Details available in ZORI methodology.```

### Files

There is an unique file to download.<br> 
* ZORI (Smoothed) All homes plus multifamily Time Series ($). ZIP Codes. ***Zip_ZORI_AllHomesPlusMultifamily_Smoothed.csv***
* ZORI (Smoothed) All homes plus multifamily Time Series ($). Metro & US. ***Metro_invt_fs_uc_sfrcondo_sm_month.csv***

### Number of rows

* ***Zip_ZORI_AllHomesPlusMultifamily_Smoothed.csv***<br>
  Rows: 2419<br>
  Facts per Row: 2014-01 to 2022-06. 102 price months per row.<br>
  Total: 246738 Facts. <br>

* ***Metro_invt_fs_uc_sfrcondo_sm_month.csv***<br>
  Rows: 918 <br>
  Facts per Row: 2018-01 to 2022-06. 54 price months per row.<br>
  Total: 49572 Facts. <br>
  
### Fields

* ***Zip_ZORI_AllHomesPlusMultifamily_Smoothed.csv***<br>




* ***Metro_invt_fs_uc_sfrcondo_sm_month.csv***<br>

  * ***RegionId***: 6 digits, Region Code, .<br> 
  * ***SizeRank***: Numerical, autoincremental.<br>
  * ***RegionName***: String, description or name of region.<br> 
  * ***RegionType***: String, type of region.
  * ***Price_for_2018_01***: Numerical, price of rental in dolars
  * ***Price_for_2018_02***: Numerical, price of rental in dolars
  * ...
  * ***Price_for_2022_06***: Numerical, price of rental in dolars

  
 
 


