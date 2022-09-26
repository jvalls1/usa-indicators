
# Data Quality and Assessment

## Air Quality

* There are 14 files for each one corresponding to a substance. 
* The structure of these files are the same. 
* A field with two letters identifying the state are missing. For example '01' -> 'AL'. It can be generate easily in the 
  next stage of the pipeline. No change to original data was made. 
* There are no measures for every county. States have at last one point of observation.


## Traffic Trends

* Traffic_trends.ipnyb, is used for profiling and cleaning. The file 
* Traffic_trends.py runs for all file sets  


## Health Insurance

*  Health_insurance_profiling.ipynb, is used for profiling and cleaning. The file sahie2019.csv is used.
*  Health_insurance_profiling.py runs for all sets of files sahieXXXX.csv. 
   A file is generate form each source file:
   * Source: XXXX_sahie_county.csv > Generated: cl_XXX_sahie_country.csv
   
The following data are missing for each XXXX_sahie_county

* State: Hawai
* County: Kalawao County
* Facts: NIPR,nipr_moe,NUI,nui_moe,NIC,nic_moe,PCTUI,pctui_moe,PCTIC,pctic_moe,PCTELIG,pctelig_moe,PCTLIIC,pctliic_moe


## Causes of death

* causes_of_death.ipynb, is used for profiling and cleaning.
* causes_of_death.py, runs for the two files.

Permanent file: 2014-2019. <br>
Provisional file: 2020-2021, COVID info included. <br>

Actions taken: <br>
The two data files are joined in one file. <br>
The provisional file has 35 colums and the permanent one 30. <br>
4 Columns from provisional corresponds are for reflecting COVID deaths. <br>
1 Column from provisional is date of update. <br>
1 Column from provisional will be dropped. <br>
4 Columns form permanent will be added. <br>

Names of columns are too large. It may be difficult to treat them for coding.
The name of columns will be renamed as follows.

| New Column name | Old Column name |
| ----------------| --------------- |
| state_name      | Jurisdiction of Occurrence |                                                                        
| year            | MMWR Year       |                                                                                          
| week            | MMWR Week       |                                                                                   
| week_end_date   | Week Ending Date |
| flag_provisional| ----      |
| allcause        | All Cause |                                                                                          
| natcause        | Natural Cause |                                                                                      
| sept            | Septicemia (A40-A41) |                                                                               
| neopl           | Malignant neoplasms (C00-C97) |                                                                      
| diab            | Diabetes mellitus (E10-E14) |
| alz             | Alzheimer disease (G30) |                                                                            
| inflpn          | Influenza and pneumonia (J09-J18) |                                                                  
| clrd            | Chronic lower respiratory diseases (J40-J47) |                                                       
| otherresp       | Other diseases of respiratory system (J00-J06,J30-J39,J67,J70-J98) |                                 
| nephr           | Nephritis, nephrotic syndrome and nephrosis (N00-N07,N17-N19,N25-N27) |                              
| otherunk        | Symptoms, signs and abnormal clinical and laboratory findings, not elsewhere classified (R00-R99)|
| hd              | Diseases of heart (I00-I09,I11,I13,I20-I51) |                                                       
| stroke          | Cerebrovascular diseases (I60-I69)|                                                                 
| cov19mcod       | COVID-19 (U071, Multiple Cause of Death) |                                                           
| cov19ucod       | COVID-19 (U071, Underlying Cause of Death) |    
| flag_allcause   | flag_allcause |                                                                                     
| flag_natcause   | flag_natcause |                                                                                      
| flag_sept       | flag_sept |                                                                                           
| flag_neopl      | flag_neopl |                                                                                   
| flag_diab       | flag_diab |                                                                                          
| flag_alz        | flag_alz |                                                                                            
| flag_inflpn     | flag_inflpn |                                                                                        
| flag_clrd       | flag_clrd |                                                                                             
| flag_otherresp  | flag_otherresp |                                                                                    
| flag_nephr      | flag_nephr |                                                                                         
| flag_otherunk   | flag_otherunk |                                                                                      
| flag_hd         | flag_hd |                                                                                             
| flag_stroke     | flag_stroke |                                                                                         
| flag_cov19mcod  | flag_cov19mcod |                                                                                   
| flag_cov19ucod  | flag_cov19ucod |     

All fields that begins with 'flag_' must have values 0 or 1 <br>
,, -> 0 <br>
Other info -> 1 <br>

## Housing
### Buying Prices

### Rental Prices
   
## Personal Economy

### Per Capita Personal Income

* PCPI_profiling.ipynb, is used for profiling and cleaning. 
* PCPI_profiling.py runs for all set of files. 

### Unemployment

* unemployment.ipynb, is used for profiling and cleaning. 
* unemployment.py runs for all set of files. 
77 Counties belonging to Puerto Rico has no data<br>

