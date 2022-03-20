# Data analysis using Python

    Main libraries used:
    
       - Data manipulation: numpy, pandas
       
       - Data visualization: matplotlib, seaborn
       
       - Geospatial data visualization: geopandas, folium
         
- - - -
## Personal Work

## 1. Greek refugee crisis.

- Kaggle link: https://www.kaggle.com/leandrosev/asylum-seekers-greece-kaggle-first-attempt
- Data downloaded from official UNHCR page. Contains info about asylum seekers in Greece, from 2000 to 2018.
- Tasks:
   - Data prerprocessing
   - Descriptive statistics
   - Data visualization (+ GeoSpatial plots)
   
![results](https://i.ibb.co/ZNJHJkx/download-3.png)
<a href="https://ibb.co/1TYqkGn"><img src="https://i.ibb.co/gJbTxZ7/results-32-0.png" alt="results-32-0" border="0" /></a>

## 2. IMDB Movie Database

   - Kaggle link: https://www.kaggle.com/leandrosev/imdb-movie-data-exploratory-analysis
   - Data from kaggle repository. Contains 1000 most popular movies on IMDB from 2006 to 2016.
   - Tasks:
      - Data Preprocessing
      - Exploratory analysis
      - Data visualization (+ wordclouds)

![imdb](https://i.ibb.co/xjxPGWV/download-4.png)
![imdb2](https://www.kaggleusercontent.com/kf/17139256/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..s7-z_GDtM8OvMwv8-ADmDw.IboZmpAA8l936Aa5spUfybVCAyUpXURjujIwZkmKvf-Xwl9BDaOLvqxmVeleddNA7aPjEfX9nwOoebjmPm-DGjxuauUIl1FnKm5hjTVXtTII4euhyu8Xs-lM5fD3XYx2lqHyss9jAQ3C2v0I-knDMA0wnpu8BLXKX7R3sH43FBpyuSJMuUSU2qH31q0OcsnZ-0H6nQJqKFN2cGOTcgpSyoE2Oin5J2B6HE36I4Dj-Tde1ozxyXUyTeZ_PwoP07m9-eaBNqyiu4k9EQJ_OAFPHNYhsC4apKMfOYpl_Aw8E3YT8JvsttNAHAzbYeICLy6nk-WwwAt0zlaDFSF1cAQhqSijzCJ46PcQz6vfaHctSUoWyilxklf4bkQuK8WVrnNPZsCsHvugy4eTRPzJx7YkTDqiGkHefsciZoUKEXck1DM5XB_Es0wpkfvSAjlJV_wgizqRx8uDoxVVWx0l8pyqzRZuIWfoVvg9P13NWfYQkAKYCv76Dd7GHVKGBJcNmfqYsXBY9u7K9dMw2-44sP_U3UQkbuWzDCH9ATGJS4sGjrPXDi3xVp-G7F3glN0cy2_WZu1OqFX65NnWBrop2D5i2mM6QGJmcZ1GKm9Q-Og6PtIyTqPaB2O59CBsMvBcNsUCCvmSFJWLctHFwV3gyo_7nlWq0KRcU1yt2QIaqaUewmXtU9uGpNTdYcgGrXGqznkD.IAELur6hguuK8BsIWBhOYg/__results___files/__results___71_0.png)
- - - -
## Simple excercises made during MSc studies

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

![ibm_stocks](https://i.ibb.co/K0Hs68g/ibm.png)

### Ex 3: World_bank_data.ipynb
   1. WDIEXCEL.zip containts economic metrics gathered by the World Bank for many years. Our countries of interest are four countries of our choice,but must include Greece and Germany. For all the metrics of the selected countries calculate the percentage of NaNs of each row (completeness). Also, calculate the largest set of consecutive data without NaNs, for each metric, starting from the most recent year.
   
   2. Connect to the World Bank API and gather the ten best economic metrics. Examine and calculate the correlation between them and use the best two in your opinion, to extract information about the selected countries.

![wb](https://i.ibb.co/0y3TDhV/download-2.png)
