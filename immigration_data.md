## Inmigration Data

This data comes from the US National Tourism and Trade Office.<br>
[Tourism and Trade office](https://www.trade.gov/national-travel-and-tourism-office)<br>
https://www.trade.gov/national-travel-and-tourism-office

## Files 

File format is parquet:

* part-00013-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00012-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00011-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00010-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00009-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00008-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00007-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00006-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00005-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00004-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00003-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00002-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy
* part-00001-b9542815-7a8d-45fc-9c67-c9c5007ad0d4-c000.snappy

### Fiels

| Field | Description |
| ------| ------------|
| I94YR | 4 digit year |
| I94MON | Numeric month  |
| I94CIT | This format shows all the valid and invalid codes for processing  |
| I94RES | This format shows all the valid and invalid codes for processing  |
| I94PORT | 3 Digits coding PORT |
| ARRDATE | is the Arrival Date in the USA. | 
| I94MODE | (1 Air, 2 Sea, 3 Land, 9 Not reported) |
| I94ADDR | 2 Digits to code State.  |
| DEPDATE | is the Departure Date from the USA. |
| I94BIR | Age of Respondent in Years  |
| I94VISA | Visa codes collapsed into three categories (1 = Business, 2 = Pleasure, 3 = Student) |
| COUNT | Used for summary statistics  |
| DTADFILE | Character Date Field - Date added to I-94 Files  |
| VISAPOST | Department of State where where Visa was issued  |
| OCCUP | Occupation that will be performed in U.S.  |
| ENTDEPA | Arrival Flag - admitted or paroled into the U.S.  |
| ENTDEPD | Departure Flag - Departed, lost I-94 or is deceased  |
| ENTDEPU | Update Flag - Either apprehended, overstayed, adjusted to perm residence  |
| MATFLAG | Match flag - Match of arrival and departure records  |
| BIRYEAR | 4 digit year of birth  |
| DTADDTO | Character Date Field - Date to which admitted to U.S. (allowed to stay until) |
| GENDER | Non-immigrant sex |
| INSNUM | INS number |
| AIRLINE | Airline used to arrive in U.S. |
| ADMNUM | Admission Number  |
| FLTNO | Flight number of Airline used to arrive in U.S. |
| VISATYPE | Class of admission legally admitting the non-immigrant to temporarily stay in U.S. | 


### Number of Records
3.000.000

### Data Preview
`(cicid=5748517.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=438.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='CA', depdate=20582.0, i94bir=40.0, i94visa=1.0, count=1.0, dtadfile='20160430', visapost='SYD', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1976.0, dtaddto='10292016', gender='F', insnum=None, airline='QF', admnum=94953870030.0, fltno='00011', visatype='B1')`<br><br>
`(cicid=5748518.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=438.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='NV', depdate=20591.0, i94bir=32.0, i94visa=1.0, count=1.0, dtadfile='20160430', visapost='SYD', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1984.0, dtaddto='10292016', gender='F', insnum=None, airline='VA', admnum=94955622830.0, fltno='00007', visatype='B1')`<br><br>
`(cicid=5748519.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=438.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='WA', depdate=20582.0, i94bir=29.0, i94visa=1.0, count=1.0, dtadfile='20160430', visapost='SYD', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1987.0, dtaddto='10292016', gender='M', insnum=None, airline='DL', admnum=94956406530.0, fltno='00040', visatype='B1')`<br><br>
`(cicid=5748520.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=438.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='WA', depdate=20588.0, i94bir=29.0, i94visa=1.0, count=1.0, dtadfile='20160430', visapost='SYD', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1987.0, dtaddto='10292016', gender='F', insnum=None, airline='DL', admnum=94956451430.0, fltno='00040', visatype='B1')`<br><br>
`(cicid=5748521.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=438.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='WA', depdate=20588.0, i94bir=28.0, i94visa=1.0, count=1.0, dtadfile='20160430', visapost='SYD', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1988.0, dtaddto='10292016', gender='M', insnum=None, airline='DL', admnum=94956388130.0, fltno='00040', visatype='B1')`<br><br>
`(cicid=5748522.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=464.0, i94port='HHW', arrdate=20574.0, i94mode=1.0, i94addr='HI', depdate=20579.0, i94bir=57.0, i94visa=2.0, count=1.0, dtadfile='20160430', visapost='ACK', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1959.0, dtaddto='10292016', gender='M', insnum=None, airline='NZ', admnum=94981802830.0, fltno='00010', visatype='B2')`<br><br>
`(cicid=5748523.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=464.0, i94port='HHW', arrdate=20574.0, i94mode=1.0, i94addr='HI', depdate=20586.0, i94bir=66.0, i94visa=2.0, count=1.0, dtadfile='20160430', visapost='ACK', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1950.0, dtaddto='10292016', gender='F', insnum=None, airline='NZ', admnum=94979689930.0, fltno='00010', visatype='B2')`<br><br>
`(cicid=5748524.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=464.0, i94port='HHW', arrdate=20574.0, i94mode=1.0, i94addr='HI', depdate=20586.0, i94bir=41.0, i94visa=2.0, count=1.0, dtadfile='20160430', visapost='ACK', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1975.0, dtaddto='10292016', gender='F', insnum=None, airline='NZ', admnum=94979746730.0, fltno='00010', visatype='B2')`<br><br>
`(cicid=5748525.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=464.0, i94port='HOU', arrdate=20574.0, i94mode=1.0, i94addr='FL', depdate=20581.0, i94bir=27.0, i94visa=2.0, count=1.0, dtadfile='20160430', visapost='ACK', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1989.0, dtaddto='10292016', gender='M', insnum=None, airline='NZ', admnum=94973246630.0, fltno='00028', visatype='B2')`<br><br>
`(cicid=5748526.0, i94yr=2016.0, i94mon=4.0, i94cit=245.0, i94res=464.0, i94port='LOS', arrdate=20574.0, i94mode=1.0, i94addr='CA', depdate=20581.0, i94bir=26.0, i94visa=2.0, count=1.0, dtadfile='20160430', visapost='ACK', occup=None, entdepa='G', entdepd='O', entdepu=None, matflag='M', biryear=1990.0, dtaddto='10292016', gender='F', insnum=None, airline='NZ', admnum=95013547930.0, fltno='00002', visatype='B2')`<br><br>
