## School Level

### Origin of data

School level is found in the CENSUS US web, under the concept of Educational Attainment.

https://www.census.gov/data/tables/time-series/demo/educational-attainment/cps-historical-time-series.html


### Files

There are four tables. 
* **taba_1.csv**: [Years of school completed by people 25 years and over, by age and sex: Selected years 1940 to 2021](https://www2.census.gov/programs-surveys/demo/tables/educational-attainment/time-series/cps-historical-time-series/taba-1.csv)
* **taba_2.csv**: [Percent of People 25 years and Over Who has completed high school or college, by Race, Hispanic Origin and Sex: Selected years 1940 to 2021](https://www2.census.gov/programs-surveys/demo/tables/educational-attainment/time-series/cps-historical-time-series/taba-2.csv)<br>
* **taba_3.csv**: [Mean Earnings of Workers 18 years and over, by Educational Attainment, race, hispanic origin and sex: 1975 to 2020](https://www2.census.gov/programs-surveys/demo/tables/educational-attainment/time-series/cps-historical-time-series/taba-3.csv)<br>
* **taba_4.csv**: [A detailed Years Completed by People of 25 Years and Over: 2000-2021](https://www2.census.gov/programs-surveys/demo/tables/educational-attainment/time-series/cps-historical-time-series/taba-4.csv)


### Fields

* taba_1.csv: <br>
  * Year: year of measure.
  * Total: total of people in thousands.
  * Dimensions:
    * Years old: 
      * 25 years and over
      * 25 to 34 years
      * 35 to 54 years
      * 55 and over
    * Sex: 
      * Both
      * Male
      * Female
 * Facts Years of School Completed:
    * Elementary I  (0 to 4 years)
    * Elementary II (5 to 8 years)
    * High School I (1 to 3 years)
    * High School II (4 years)
    * College I (1 to 3 years)
    * College II (4 years of more)   
  
* taba_2.csv: <br>
  * Year: year of measure
  * Total: total people in thousands.
  * Dimensions: 
    * Year old:
      * 25 year and over, YEARS I
      * 25 to 29 years, YEARS II     
    * Sex
      * Total
      * Male
      * Female
    * Educational Level Attainment.
      * 4 Years of High School or more, ATTAINMENT I
      * 4 Years of College or more, ATTAINMENT II  
    * Race
      * White
      * Black
      * Asian
    * Etnicitiy
      * Non-Hispanic
      * Hispanic
  * Facts for Dimensions (Year old, Educational Level Attainment, Race and Etnicity)
      * Measure in thousands, Combinations:
        * (White,Non-Hispanic)
        * (White,Hispanic)
        * (Any,Hispanic)
        * (Asian, Any)
        * (Black, Any)
        * (White + Other, Non-Hispanic)
        * (White + Other, Hispanic)
        * (Asian + Other, Any)
        * (Asian + Other, Any)
  

       
