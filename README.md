# DATAPRE-MCO3

### I. Data Dictionary for Average Temperature of Cities dataset

|Variable |	Definition	| Dtype |
|---------|---------------------|-------|
|Region	|Location of Region |	Object
Country	| Location of Country | 	Object
State	| Location of State	|float64
City	| Major Cities	| Object
Month	| Month as Integer |	Object
Day	| Day as Integer	| int64
Year	| Year as integer	| int64
AvgTemperature|	Temperature in Fahrenheit |	int64

### II. Data Dictionary for List Typhoons per Year dataset created from Webscraping

|Variable |	Definition	| Key |
|---------|---------------------|-------|
|Name	|Name of the Typhoon	|Name
|*	|Strength of Typhoon|	Symbol|
|Date	|Period of Storm Formation	|Days, Months, Years|

### III. Data Dictionary for Countries and their coordinates dataset

|Variable|	Definition|	Key|
|---------|---------------------|-------|
Country|	Country's name	|String
Year	|Year taken from data|	Integer
AvgTemperature|	Temperature of the country in Celsius	|Float
Latitude	|Country's Alpha-2 Code |	String
Longitude	|Latitude in degrees	|Float
Name	|Longitude in degrees|	Float
Country	|Country's name	String|


### I. Data Dictionary for Food and Agriculture Organization of the United Nations dataset	
|Variable|	Definition|	Key|
|---------|---------------------|-------|
|Country|	Country's name|	String|
|Year|	Year taken from data	|Integer|
|Mean Temp|	Temperature of the country in Celsius|	Float|
|Latitude|	Country's Alpha-2 Code|	String|
|Longitude|	Latitude in degrees|	Float|
|Country Code|	Longitude in degrees|	Float|

## Steps to Access the File

1. Download the whole repository
2. Unzip the data_set zip file and place the extracted csvs in the same location with the `main` file
3. Run the file using Jupyter Notebook

## Reference

Knapp, K. (n.d.). Storms by year and Basin. IBTrACS. Retrieved July 6, 2022, from http://ibtracs.unca.edu/index.php?name=browse-year-basin 
Krishnaswami, N. (2019, July 9). DSPL/countries.csv at master · google/DSPL. GitHub. Retrieved July 6, 2022, from https://github.com/google/dspl/blob/master/samples/google/canonical/countries.csv 
Rajkumar, S. (2020, June 5). Daily temperature of major cities. Kaggle. Retrieved July 6, 2022, from https://www.kaggle.com/datasets/sudalairajkumar/daily-temperature-of-major-cities 
© FAO. FAOLEX Database. [Temperature Change]. License: CC BY-NC-SA 3.0 IGO. Extracted from: www.fao.org/faolex/opendata.
