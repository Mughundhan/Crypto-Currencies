# Crypto-Currencies - Data Extraction, Segmentation, Comparative Analysis, Short-term Price Prediction
An automated data pipeline for extracting crypto-currencies historical data, perform comparative analysis (computing volatility rate, financial ratios) and build regression models to predict short-term price trends of stable crypto-currencies.

Client - Morningstar Inc., Chicago, IL

#### NOTE: The code for data engineering, analysis and prediction will not be made public as there are talks to make a publication on achieving the target accuracy. However, the automated text file which is generated and e-mailed after successful completion of Daily data extraction for 1600+ crypto-currencies is uploaded in this repository.


#### Project Overview:

##### 1.	Project: Crypto-currencies Data Engineering | Client: Morningstar Inc., - Chicago, IL | Tools used: Python, Jupyter Notebook, Atom, MySQL Workbench, Cron
###### •	Bulk Data Acquisition: Designed a Web Scraping Engine to extract over million rows (2013-18 historical data including ticker information for 1600+ crypto-currencies) from the target website and push into MySQL database. 
###### •	Periodic Data Extraction: Designed a Web Scraping Engine for automated-periodic data extraction from the target website (extract daily-transaction data of 1600+ crypto-currencies). The extracted data is automatically appended to MySQL database. 

##### 2.	Project: Cryptocurrencies Data Analysis | Client: Morningstar Inc., - Chicago, IL | Tools used: Python, R Shiny, ARIMA, Statistics
###### •	Cluster Analysis: Computed average daily volatility rate and segmented 1600+ crypto-currencies using K-means Clustering.
###### •	Exploratory Data Analysis: Captured the price trends of crypto-currencies. Stationarized the series to eliminate trend and seasonality.
###### •	Value Forecasting: Built SVM and Linear Regression models to forecast short-term price trends of stable crypto-currencies.

###### NOTE: The web scraping engine automatically handles duplications, data cleansing, identifies newly added crypto-currencies and start extracting daily information of newly added crypto-currencies and sends an auto-generated E-mail with a text file comprising of all new crypto-currencies information and time-taken for the update).
