### Population

#### Origin of data 

Data: [SEER organization](https://seer.cancer.gov/popdata/download.html)

### Files

Available Files:
  County level files, Single-year Age Group
  
  1960-2020. Races: White, Black, Other. <br> 
  https://seer.cancer.gov/popdata/yr1969_2020.singleages/us.1969_2020.singleages.adjusted.exe => gz, 238.8 MB<br>
  rows:  x <br>
  
  1990-2020. 4 Expanded Races by Origin. <br>
  https://seer.cancer.gov/popdata/yr1990_2020.singleages/us.1990_2020.singleages.adjusted.exe => gz, 246.3 MB<br> 
  rows: 65160149 <br> 
  
  Update frequency and policy:
  Annually and each year all data are corrected.
  
### File Format 
  
    * Fixed length ASCII text records (26 Bytes)
    * One Population per record/line 
    * Windows (CR/LF) line delimiters
    * All numeric data is zero filled to the left
    
 <table>
    	<thead>
		  <tr> 
		    <th scope="col">Variable Name and Values</th>
		    <th scope="col">Start Column</th>
		    <th scope="col">Length</th>
		    <th scope="col">Data Type</th>
		  </tr>
  	  </thead>
  <tr> 
    <td><strong>Year</strong><br>
      (1969, 1970, 1971...)</td>
    <td>1</td>
    <td>4</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td><strong>State postal abbreviation</strong><br>
    &quot;KR&quot; is used for the dummy state created to represent hurricane  Katrina/Rita evacuees</td>
    <td>5</td>
    <td>2</td>
    <td>character</td>
  </tr>
  <tr> 
    <td><strong>State FIPS code<br>
    </strong>Field is 9-filled for  dummy state created to represent hurricane  Katrina/Rita evacuees </td>
    <td> 
      <div>7</div>
    </td>
    <td> 
      <div>2</div>
    </td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td><strong>County FIPS code</strong><br>
    Field is 9-filled for dummy state created to represent hurricane Katrina/Rita evacuees</td>
    <td>9</td>
    <td>3</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td> 
      <dl> 
        <dt><strong>Registry (Geographic Definition Only)</strong></dt>
        <dd>01 = San Francisco-Oakland SMSA</dd>
        <dd>02 = Connecticut</dd>
        <dd>20 = Detroit (Metropolitan)</dd>
        <dd>21 = Hawaii</dd>
        <dd>22 = Iowa</dd>
        <dd>23 = New Mexico</dd> 
        <dd>25 = Seattle (Puget Sound)</dd>
        <dd>26 = Utah</dd>
        <dd>27 = Atlanta (Metropolitan)</dd>
        <dd>29 = Alaska</dd>
        <dd>31 = San Jose-Monterey</dd>
        <dd>33 = Arizona</dd>
        <dd>35 = Los Angeles</dd>
        <dd>37 = Rural Georgia</dd>
        <dd>41 = California excluding SF/SJM/LA</dd>
        <dd>42 = Kentucky</dd>
        <dd>43 = Louisiana</dd>
        <dd>44 = New Jersey</dd>
        <dd>47 = Georgia excluding Atlanta/Rural Georgia</dd>
        <dd>61 = Idaho</dd>
		<dd>62 = New York</dd>
		<dd>63 = Massachusetts</dd>
		<dd>99 = Registry for non-SEER area</dd>
      </dl>
    </td>
    <td>12</td>
    <td>2</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td>
    <dl> 
  <dt><strong>Race</strong><br>
    1969+ data:</dt>
        <dd>1 = White</dd> 
        <dd>2 = Black</dd> 
        <dd>3 = Other</dd> 
        <dt>1990+ data:</dt>
        <dd>1 = White</dd> 
        <dd>2 = Black</dd> 
        <dd>3 = American Indian/Alaska Native</dd> 
        <dd>4 = Asian or Pacific Islander</dd> 
    </dl>
    </td>
    <td>14</td>
    <td>1</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td>
      <dl> 
        <dt><strong>Origin</strong><br>
         Applicable to 1990+ data: 
        </dt> 
        <dd>0 = Non-Hispanic</dd> 
        <dd>1 = Hispanic</dd> 
        <dd>9 = Not applicable in 1969+ W,B,O files</dd>
      </dl>
    </td>
    <td>15</td>
    <td>1</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td> 
      <dl> 
        <dt><strong>Sex</strong></dt>
        <dd>1 = Male</dd>  
        <dd>2 = Female</dd>  
      </dl>
    </td>
    <td>16</td>
    <td>1</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td> 
      <dl> 
        <dt><strong>Age</strong><br>
					   19 Age group data:</dt>
        <dd>00 = 0 years</dd>  
        <dd>01 = 1-4 years</dd>  
        <dd>02 = 5-9 years</dd>  
        <dd>03 = 10-14 years</dd>  
        <dd>04 = 15-19 years</dd>  
        <dd>&#133;</dd>  
        <dd>17 = 80-84 years</dd>  
        <dd>18 = 85+ years</dd>  
        <dt>Single age data:</dt>
        <dd>00 = 0 years</dd>  
        <dd>01 = 1 years</dd>  
        <dd>02 = 2 years</dd>  
        <dd>&#133;</dd>  
        <dd>84 = 84 years</dd>  
        <dd>85 = 85+ years</dd>  
      </dl>
    </td>
    <td>17</td>
    <td>2</td>
    <td>numeric</td>
  </tr>
  <tr> 
    <td><strong>Population</strong></td>
    <td>19</td>
    <td>8</td>
    <td>numeric</td>
  </tr>
  </table>   
  
  #### Row examples of data.
  
  ``1990AL01003992017500000026``<br>
  ``1990AL01003992017600000026``<br>
  ``1990AL01003992017700000020``<br> 
  ``1990AL01003992017800000015``<br>
  
  * Year: 1990
  * State: AL (Alabama)
  * County: 01003 Alabama, Baldwin County.
  * 99: Data that comes from external organization.
  * 20: Black, non Hispanic
  * 1:  Male
  * (75 years : 26 Inhabitants, 76 years: 26 Inhabitans, 77 years: 20 Inhabitants, 78: 15 Inhabitants)
  
	
  
 
