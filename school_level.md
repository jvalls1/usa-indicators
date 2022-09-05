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
        
  * taba_3.csv <br>
    * Year: year of measure
    * Aggregate value:
      * Total: Number of people with earnings
      * Mean: Mean of earnings
      * Standard Error: Standard error.
    * Dimensions
      * Educational Attainment. 
        * Not a high school graduate
        * High school graduate
        * Some college
        * Bachelor degree
        * Advanced degree
      * Sex
        * Both
        * Male
        * Female
      * Race
        * White
        * Black
        * Asian
      * Etnicitiy
        * Non-Hispanic
        * Hispanic    
    * Facts
      * Number of people with earnings
      * Mean of earning
      * Standard Error
      (Facts for these dimensions)
      (Educational Attainment,Sex,Race,Etnicity)
        * (Educational Attaiment,Sex,White,Non-Hispanic)
        * (Educational Attaiment,Sex,White,Hispanic)
        * (Educational Attaiment,Sex,Any,Hispanic)
        * (Educational Attaiment,Sex,Asian, Any)
        * (Educational Attaiment,Sex,Black, Any)
        * (Educational Attaiment,Sex,White + Other, Non-Hispanic)
        * (Educational Attaiment,Sex,White + Other, Hispanic)
        * (Educational Attaiment,Sex,Asian + Other, Any)
        * (Educational Attaiment,Sex,Asian + Other, Any)
  
* taba_4.csv <br>
  * Year of measure (2000,...,2021)
  * Aggregate value:
    * Total
  * Dimensions:
    * Education Attainment
       * Elementary or High school, no diploma
         *	Less than 1 year, no diploma
         *	1st-4th grade, no diploma
         * 5th-6th grade, no diploma
         * 7th-8th grade, no diploma
         *	9th grade, no diploma
         * 10th grade, no diploma
         * 11th grade, no diploma
         * 12th grade, no diploma"
      * Elementary or High school, GED																																												
         * Less than 1 year, GED
         * 1st-4th grade, GED
         * 5th-6th grade, GED
         * 7th-8th grade, GED
         * 9th grade, GED
         * 10th grade, GED
         * 11th grade, GED
         * 12th grade, GED
         * High school diploma
      * College, no degree																																												
         * Less than 1 year college, no degree
         * One year of college, no degree
         * Two years of college, no degree
         * Three years of college, no degree
         * Four or more years of college, no degree
      * Associate's degree, vocational																																												
         * Less than 1 year college, vocational/associate's
         * One year of college, vocational/associate's
         * Two years of college, vocational/associate's
         * Three years of college, vocational/associate's
         * Four or more years of college, vocational/associate's
      * Associate's degree, academic																																												
         * Less than 1 year college, academic/associate's
         * One year of college, academic/associate's
         * Two years of college, academic/associate's
         * Three years of college, academic/associate's
         * Four or more years of college, academic/associate's"
      * Bachelor's degree
         * Bachelor's degree 
         * Bachelor's degree only 
      * Master's degree program
         * Master's degree only
         * Master's degree 1 year program
         * Master's degree 2 years program
         * Master's degree 3 or more years program
      * Professional or Doctorate degree																																												
         * Professional degree
         * Doctorate degree"
   * Facts
       * Number of people       
       * Percent
 
 
   
       
