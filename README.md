# Data analysis using Python
- - - -
## Personal Work

## 1. Analyzing Greek refugee crisis.

- Kaggle link: https://www.kaggle.com/leandrosev/asylum-seekers-greece-kaggle-first-attempt
- Data downloaded from UNHCR page. Contains info for asylum seekers from 2000 to 2018.
- Includes:
   - Data prerprocessing
   - Descriptive statistics
   - Data visualization (+ GeoSpatial plots)
- Libraries used:
   - numpy,pandas
   - matplotlib,seaborn
   - geopandas,folium


- - - -
## Excercises made during MSc studies

### Ex 1: nlp.ipynb
   - Calculate the letter frequency of a text file and compare it to the standard letter frequencies of the english alphabet

### Ex 2: stocks.ipynb
   1. Download from https://finance.yahoo.com/quote/IBM/history?p=IBM , IBM's stock values from 01/01/1962 up to date
   2. Find the percentage daily variance of the stock: 100*(open_value - close_value)/open_value
      and add a new column in a new excel file 
   3. Create a histogram where x = daily variance percentage, y = number of days with that variance percentage
      In the same plot add max and min values with their corresponding dates (Seaborn,Matplotlib)
   4. Use a statistical model to fit the data and plot it in the same plot (Scipy)
   5. Automate the above procedure 

### Ex 3: World_bank_data.ipynb
   1. WDIEXCEL.zip containts economic metrics gathered by the World Bank for many years. Our countries of interest are four countries of our choice,but must include Greece and Germany. For all the metrics of the selected countries calculate the percentage of NaNs of each row (completeness). Also, calculate the largest set of consecutive data without NaNs, for each metric, starting from the most recent year.
   
   2. Connect to the World Bank API and gather the ten best economic metrics. Examine and calculate the correlation between them and use the best two in your opinion, to extract information about the selected countries.
