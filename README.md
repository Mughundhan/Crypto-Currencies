# Crypto-Currencies - Data Extraction, Segmentation, Comparative Analysis, Short-term Price Prediction
An automated data pipeline for extracting crypto-currencies historical data, perform comparative analysis (computing volatility rate, financial ratios) and build regression models to predict short-term price trends of stable crypto-currencies.

Client - Morningstar Inc., Chicago, IL

#### NOTE: The code for data engineering, analysis and prediction will not be made public as there are talks to make a publication on achieving the target accuracy. However, the automated text file which is generated and e-mailed after successful completion of Daily data extraction for 1600+ crypto-currencies is uploaded in this repository.


#### Project Overview:

##### 1.	Project: Crypto-currencies Data Engineering | Client: Morningstar Inc., - Chicago, IL | Tools used: Python, Jupyter Notebook, Atom, MySQL Workbench, Cron
###### •	Bulk Data Acquisition: Designed Web Scrapers and an automated data pipeline. Extracted over million rows (2013-18 historical data for 1600+ crypto-currencies) from target website and dumped the extracted data to MySQL database. 
###### •	Periodic Data Extraction: Built a robust channel for automated-periodic data extraction from the web and to append the extracted data to MySQL database. (Automatically handles duplications, data cleansing, missing values and change of ranks)

##### 2.	Project: Cryptocurrencies Data Analysis | Client: Morningstar Inc., - Chicago, IL | Tools used: Python, R Shiny, ARIMA, Statistics
###### •	Cluster Analysis: Computed average daily volatility rate and segmented 1600+ crypto-currencies using K-means Clustering.
###### •	Financial Analysis: Analyzed risk adjusted returns (evaluated Sharpe Ratio, Information Ratio) and performed portfolio comparison.
###### •	Value Forecasting: Built SVM and Linear Regression models to forecast short-term price trends of stable crypto-currencies.
###### •	Business Intelligence: Designed R Shiny Web app to effectively demonstrate the performance of stable crypto-currencies and classification of crypto-currencies.
