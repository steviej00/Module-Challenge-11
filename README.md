# Module-Challenge-11

# Forecasting Net Prophet

I am working as growht anaylis for MercadoLibre. With over 200 million users, MercadoLibre is an attractive e-commerce site in Latin America. I've been assigned to analyiz the company's financial and user data in clever ways to make the company expand. With the ability to predict search traffic can translate into the capability to successfully trade the stock.

# Step 1: Find Unusual Patterns in Hourly Google Search Traffic



# Step 2: Mine the Search Traffic Data for Seasonality




# Step 3: Relate the Search Traffic to Stock Price Patterns




# Step 4: Create a Time Series Model with Prophet




# Step 5 (Optional): Forecast Revenue by Using Time Series Models



# Installs and import the required libraries and dependencies

INSTALLS
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

IMPORTS
from pathlib import Path 
import numpy as np
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline

