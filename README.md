# Predictive Analytics : Predict the weekly aggregated sales four weeks in advance
<br>
 <h2> Dataset description and source </h2>
 <hr>
The dataset used in this demonstration can be found in the UCI machine learning repository and it can be accessed via <a href = 'https://www.kaggle.com/mashlyn/online-retail-iiuci'>this link</a>.
<br><br>
<blockquote>"This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers."</blockquote>
<br>

It contains 8 attributes which are fully described below:
- InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.  
- StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.  
- Description: Product (item) name. Nominal.  
- Quantity: The quantities of each product (item) per transaction. Numeric.  
- InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.  
- UnitPrice: Unit price. Numeric, Product price per unit in sterling.  
- CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.  
- Country: Country name. Nominal, the name of the country where each customer resides.

<br>
 <h2> Flow of the project </h2>
<hr> 
In this documentation, a thorough analysis on the data is presented. Also, several time-series algorithms were used to make predictions for the aggregated weekly sales for four weeks ahead. The steps taken to achieve this were based on conventional Data Science Life Cycle:

Step 1:  <a href='https://github.com/DrUkachi/online_retail_project/blob/main/online_retail_data_wrangling.ipynb'>Data Wrangling Step</a> 

This was necessary to achieve cleaned and well-preprocessed data was fed into the analysis step. In this step data cleaning activities were carried, proper and proper data formatting was acheived.

Step 2: <a href='https://github.com/DrUkachi/online_retail_project/blob/main/online_retail_EDA.ipynb'>Exploratory Data Analysis Step</a> 

Here, a rigorous inspection of the data is carried out to extract useful insights about the data. This provides an overview of possible patterns that the data provides.

Step 3: <a href='https://github.com/DrUkachi/online_retail_project/blob/main/online_retail_time_series_analysis.ipynb'>Exploratory Time Series Analysis</a> 

This step involves going deeper into the time series analysis by exploring possible trends, seasonality and errors. In this section test for stationarity  is carried out and several observations are carried out using Auto-correlation Function (ACF) Plots and Partial Auto-correlation plots (PACF)

Step 4: <a href='https://github.com/DrUkachi/online_retail_project/blob/main/online_retail_time_series_forecasting.ipynb'>Time Series Forecasting</a>

In this step, the time-series forecasting was carried out. Here, several algorithms were used to carry out both univariate and multivariate forecasting. Also, a number of metrics were used to measure the models that gave the best results.

<br>
<h2> Implementation </h2>
<hr>
This project was carried out using Python. The codes and steps taken were properly documented in their respective Jupyter Notebooks. The project was carried out so that the corresponding codes can be seen with the documentations as certain questions were answered using these visualisations.

The required libraries for complete implementation can be found in the <a href='https://github.com/DrUkachi/online_retail_project/blob/main/requirements.txt'>requirements</a> file.
