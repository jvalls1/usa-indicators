
### Life expectancy 

#### Source of data
[Global health data exchange](https://ghdx.healthdata.org/us-data)

<p> United States Mortality rates and life expectancy by
County, Race, and Etnicity 2000-2019. </p>

Terms and Conditions of Data Use:

Data made available for download on IHME Websites can be used, shared, modified or built upon by non-commercial users in accordance with the IHME FREE-OF-CHARGE NON-COMMERCIAL USER AGREEMENT. For more information (and inquiries about commercial use), visit IHME Terms and Conditions.

Four files:

* [Life expectancy estimates 2000-2004](https://ghdx.healthdata.org/sites/default/files/record-attached-files/IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_2004.zip)<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_2004.zip
* [Life expectancy estimates 2005-2009](https://ghdx.healthdata.org/sites/default/files/record-attached-files/IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2005_2009.zip)<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2005_2009.zip
* [Life expectancy estimates 2010-2014](https://ghdx.healthdata.org/sites/default/files/record-attached-files/IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2010_2014.zip)<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2010_2014.zip
* [Life expectancy estimates 2015-2019](https://ghdx.healthdata.org/sites/default/files/record-attached-files/IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2015_2019.zip)<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2015_2019.zip

What's inside the zip files? Each zip contains files related to 5 years.

For each year:<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_XXXX_BOTH_Y2022M06D16
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_XXXX_FEMALE_Y2022M06D16
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_XXXX_MALE_Y2022M06D16

For exemple for year 2000:<br>
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_BOTH_Y2022M06D16
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_FEMALE_Y2022M06D16
IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_MALE_Y2022M06D16

#### Fields.

<table>
  <thead>
    <tr>
      <th>Variable</th>
      <th>Variable Label</th>
      <th>Variable Definition</th>
    </tr>
  </thead>
  <body>
    <tr>
      <td>measure_id</td>
      <td>Measure Id</td>
      <td>A unique numeric identifier for the measure
          generated and stored in an IHME database of
          data dimensions</td>
    </tr>
    <tr>
      <td>measure_name</td>
      <td>Measure Name</td>
      <td>The measure (indicator) for the estimate.</td>
    </tr>
    <tr>
      <td>location_id</td>
      <td>Location Id</td>
      <td>A unique numeric identifier for the location
          generated and stored in an IHME database of
          data dimensions.</td>
    </tr>
    <tr>
      <td>location_name</td>
      <td>Location Name</td>
      <td>The location for the estimate.</td>
    </tr>
    <tr>
      <td>fips </td>
      <td>FIPS Code</td>
      <td>The FIPS code for the estimate.</td>
    </tr>
    <tr>
      <td>race_id </td>
      <td>Race/ethnicity ID</td>
      <td>
          A unique numeric identifier for the
          race/ethnicity generated and stored in an IHME
          database of data dimensions
      </td>
    </tr>
    <tr>
      <td>race_name </td>
      <td>Race/ethnicity name </td>
      <td>
          The race/ethnicity for the estimate. All groups
          besides Latino and Total are non-Latino (e.g.
          non-Latino White). <br>
          Values: Total, Latino, Black. White, AIAN
          [American Indian and Alaska Native], API [Asian
          and Pacific Islander]
      </td>
    </tr>
    <tr>
      <td>sex_id</td>
      <td>Sex Id</td>
      <td>
        A unique numeric identifier for the sex
        generated and stored in an IHME database of
        data dimensions
      </td>
    </tr>
    <tr>
      <td>sex_name</td>
      <td>Sex Name</td>
      <td>The gender for the estimate.</td>
    </tr>
    <tr>
      <td>age_group_id</td>
      <td>Age Group Id</td>
      <td>A unique numeric identifier for the age group
      generated and stored in an IHME database of
      data dimensions.</td>
    </tr>
    <tr>
      <td>age_name</td>
      <td>Age Name Group</td>
      <td>The age group for the estimate.</td>
    </tr>
    <tr>
      <td>year</td>
      <td>Year</td>
      <td>The time period for the estimate.</td>
    </tr>
    <tr>
      <td>metric_id</td>
      <td>Metric Id</td>
      <td>A unique numeric identifier for the metric.</td>
    </tr>
    <tr>
      <td>metric_name</td>
      <td>Metric Name</td>
      <td>The metric/unit of measure for the estimate.</td>
    </tr>
    <tr>
      <td>val</td>
      <td>Value</td>
      <td>Mean estimate.</td>
    </tr>
    <tr>
      <td>upper</td>
      <td>
        95% Uncertainty Interval
        (Upper Bound)
      </td>
      <td>97.5% percentile estimate.</td>
    </tr>
    <tr>
      <td>lower</td>
      <td>
          95% Uncertainty Interval
          (Lower Bound)
      </td>
      <td>2.5% percentile estimate.</td>
    </tr>
  </body>
</table>

#### Example of Data.


measure_id,measure_name,location_id,location_name,fips,race_id,race_name,sex_id,sex_name,age_group_id,age_name,year,metric_id,metric_name,val,upper,lower<br><br>
26,Life expectancy,102,United States of America,,1,Total,1,Male,28,<1 year,2000,1,Number,74.1076076431798,74.1433043794098,74.0724211002904<br><br>
26,Life expectancy,102,United States of America,,2,Latino,1,Male,28,<1 year,2000,1,Number,76.6530723903737,76.9621118508913,76.3690552241845<br><br>
26,Life expectancy,102,United States of America,,4,Black,1,Male,28,<1 year,2000,1,Number,67.9188212704537,68.0557479581951,67.7964749834534<br><br>
26,Life expectancy,102,United States of America,,5,White,1,Male,28,<1 year,2000,1,Number,74.6907480351783,74.7429581392115,74.6417075045727<br><br>
26,Life expectancy,102,United States of America,,6,AIAN,1,Male,28,<1 year,2000,1,Number,70.3385698373321,72.0485027019328,68.7262461104907<br><br>
26,Life expectancy,102,United States of America,,7,API,1,Male,28,<1 year,2000,1,Number,80.206080498676,80.7672123977158,79.5638567183248<br><br>
26,Life expectancy,102,United States of America,,2,Latino,1,Male,5,1 to 4,2000,1,Number,76.1077202127294,76.4021420835275,75.8323679218532<br><br>
26,Life expectancy,102,United States of America,,4,Black,1,Male,5,1 to 4,2000,1,Number,67.9828740685329,68.0976196078829,67.8768627176185<br><br>
  

#### Aprox Number of Records.
  
For example:<br>
wc -l IHME_USA_LE_COUNTY_RACE_ETHN_2000_2019_LT_2000_MALE_Y2022M06D16.CSV<br>
365941 ~ 365000 rows.
There are 15 files into each ZIP => 24,500,000 per zip<br>
We have 4 zips => 100,000,000 rows.<br>
  
  
  



