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
![map](https://www.kaggleusercontent.com/kf/16787344/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..W5_OwTaGRYEmm2PX1rWwMw.c4V2F5T2SPR076gyv9Jr-ldxFdhd_6Syyzqr1Rss272WEQ2RX2CVojmG26iZIrKrzZPVUTr7zCvX1ie-qvs0754_qFEFuFAZD36onC3K-N7cCD55QSr0SjIjVVVAZPDaibAxEye8YsFwffAZUrk2ZDwjtRuR2q2ZdRHdJ4GwVWYe7meK3u2miav6vmUGVfy5NDJg--0rz-Q3gUFERzuSkET_D0lHo9K61vmLeOURWPuyjN_h3U3AaiICp8ErEV_7gTHoNSWCjaljxGGfCdK8c7MipXDTYIAW4DbFdyAmTPfseqZK-1u0qVI09PPnKancIsXWLgdSpRSYXoSSKjMKnCT9j49r_7TFmHs4b08yvEKLNZgh9BnrwJ8ISYyisszXzw-exT_GV2d4ByAFMn_y1YI7ShJ9940D5B_q9mAq7hEOLhEEpEd8nwRGnx_LmE_4scD01YzsrdbgddZ2EusGi0e8skm255jGRqOXYJyXgbmvBFfMwch6P0lz8K0G2Py-vWyGMEXF6MLMcFIMUyjbqYEr5GHPV8ATAeOif2tujGQUsqqoVeqObfDRowAki25SCCTDmWnx0bfkepcaHHm05XDG-22lNKuTByJpqnriwaVec8_7lyvRUaVFT1L4szjgG6MlK3Nu-uM05I4QzqhLgueLuSQ2nBWkF8Stlp1Ixxg.35DYtLToDVJoQmDoKAmcsA/__results___files/__results___32_0.png)


## 2. IMDB Movie Database

   - Kaggle link: https://www.kaggle.com/leandrosev/imdb-movie-data-exploratory-analysis
   - Data from kaggle repository. Contains 1000 most popular movies on IMDB from 2006 to 2016.
   - Tasks:
      - Data Preprocessing
      - Exploratory analysis
      - Data visualization (+ wordclouds)

![imdb](https://i.ibb.co/xjxPGWV/download-4.png)
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
