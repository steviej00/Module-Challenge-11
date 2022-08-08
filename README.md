# Module-Challenge-11

# Forecasting Net Prophet

I am working as growht anaylis for MercadoLibre. With over 200 million users, MercadoLibre is an attractive e-commerce site in Latin America. I've been assigned to analyiz the company's financial and user data in clever ways to make the company expand. With the ability to predict search traffic can translate into the capability to successfully trade the stock.

# Step 1: Find Unusual Patterns in Hourly Google Search Traffic
<img width="824" alt="image" src="https://user-images.githubusercontent.com/105945472/183479326-888b3274-9579-42b7-ab48-d09f38811c19.png">

<img width="820" alt="image" src="https://user-images.githubusercontent.com/105945472/183479045-dc957ca3-7ba9-4a3d-9fc9-68b56e242773.png">

<img width="814" alt="image" src="https://user-images.githubusercontent.com/105945472/183479516-7c8f6c81-5a80-4e56-83e3-9736b05b1860.png">

# Step 2: Mine the Search Traffic Data for Seasonality
<img width="610" alt="image" src="https://user-images.githubusercontent.com/105945472/183479622-dcefe811-6c80-4f41-af93-c174e1d21934.png">

<img width="820" alt="image" src="https://user-images.githubusercontent.com/105945472/183479935-b2bd905d-992a-4209-b0c5-ef1d1446c651.png">

<img width="605" alt="image" src="https://user-images.githubusercontent.com/105945472/183480068-6aa9b703-2a7f-4762-9682-aa4ee5d67fb4.png">

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

