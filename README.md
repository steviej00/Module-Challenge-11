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
<img width="826" alt="image" src="https://user-images.githubusercontent.com/105945472/183480409-4fc80211-a3ef-48b2-bfb2-faba4ebaa2f2.png">

<img width="740" alt="image" src="https://user-images.githubusercontent.com/105945472/183480525-5e80d306-1218-4ba6-a822-b08e801e31c3.png">

<img width="809" alt="image" src="https://user-images.githubusercontent.com/105945472/183480641-71386afd-c74b-4de3-ba58-b3c1b963d9e1.png">

<img width="540" alt="image" src="https://user-images.githubusercontent.com/105945472/183480904-c83b1c39-bf0f-4532-8473-fa7ea9688eb6.png">

<img width="818" alt="image" src="https://user-images.githubusercontent.com/105945472/183481385-f49ccd4f-0e3e-48ff-89e6-210bb475a1f8.png"><img width="830" alt="image" src="https://user-images.githubusercontent.com/105945472/183481471-3e6253d0-49d9-4404-bc09-b01c203f3cc4.png">

<img width="812" alt="image" src="https://user-images.githubusercontent.com/105945472/183481730-01f24752-e88e-45d6-8f1c-8fdf7e8fdd1f.png">

<img width="503" alt="image" src="https://user-images.githubusercontent.com/105945472/183481916-3f56e6dd-fde2-4c98-9512-56a0504bc45d.png">

<img width="546" alt="image" src="https://user-images.githubusercontent.com/105945472/183482021-c3f5a355-77b8-459f-a7de-568ca456135b.png">

# Step 4: Create a Time Series Model with Prophet
<img width="819" alt="image" src="https://user-images.githubusercontent.com/105945472/183482301-b15bbd31-23bc-4c02-b4ff-b1ae2cc77b0e.png">

<img width="490" alt="image" src="https://user-images.githubusercontent.com/105945472/183482761-8757e58d-565a-4faa-8187-8a31e8d69d1d.png">

<img width="616" alt="image" src="https://user-images.githubusercontent.com/105945472/183482875-9a4ed2d4-e34d-4a40-97b4-d2f187997c32.png">

<img width="359" alt="image" src="https://user-images.githubusercontent.com/105945472/183483098-ec2044b2-af51-483b-aca9-8b4938c3f816.png">

# Step 5 (Optional): Forecast Revenue by Using Time Series Models
<img width="454" alt="image" src="https://user-images.githubusercontent.com/105945472/183483232-f4876e9c-de67-4ea7-961f-98db976c5234.png">

<img width="650" alt="image" src="https://user-images.githubusercontent.com/105945472/183483357-0f88bacc-affa-4e5b-a32b-81393089f094.png">

<img width="514" alt="image" src="https://user-images.githubusercontent.com/105945472/183483470-bf341e49-a903-47c0-8940-c78e9d42b73f.png">

<img width="390" alt="image" src="https://user-images.githubusercontent.com/105945472/183483546-a5cad2e0-0e25-45f6-9f6d-3e392b58353b.png">

<img width="542" alt="image" src="https://user-images.githubusercontent.com/105945472/183483657-f514916b-af66-4e56-bb2b-5863b456a164.png">


# Installs and import the required libraries and dependencies

## INSTALLS
!pip install pystan
!pip install fbprophet
!pip install hvplot
!pip install holoviews

## IMPORTS
from pathlib import Path 
import numpy as np
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline

