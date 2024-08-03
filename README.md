# Week 8 Prophet Challenge

## Analyze Mercado Libre's search traffic and stock price to determine if the ability to predict search traffic can translate into the ability to successfully trade the stock.

### Step 1: Find unusual patterns in hourly Google search traffic.
* Mercado Libre released its quarterly financial results in May 2020.
* Total search trends in May 2020 were 31818, 8% higher than the median search trends in other months, which were 35172.
* Google search traffic did increase during the month when Mercado Libre released its financial results.

### Step 2: Mine the search traffic data for seasonality.
* Hourly analysis - Search traffic is at its highest between 10PM and 2AM and at its lowest between 5AM and 10AM.
* Day of Week analysis - Search traffic is higher on weekdays, peaks on Tuesdays and is lower on weekends.
* Monthly analysis - Search traffic had a few dips each year, around public holidays and is lower during the winter holiday period of September to mid-October.

### Step 3: Relate the search traffic to stock price patterns.
* When analyzing stock price trends to search traffic, there was very weak correlation found between lagged search trends and stock volatility or hourly stock price returns.
* There was a significant drop in stock closing price and search trends between March and April 2020, likely related to the pandemic and the global stock market trends.
* For the remainder of 2020, Mercado Libre stock price kept going up, similar to trends seen for other e-commerce platforms.

### Step 4: Create a time series model with Prophet.
* Used Prophet to create a predictive model for Mercado Libre search trends.
* The predictive model for 80 days after July 2020 showed a decline in search trends for Mercado Libre.

## Conclusion
### Mercado Libre search traffic trends cannot be used to predict its stock price or successfully trade the stock.

## Sources of code
All of my code is based on code provided in Week 7 (Visualization) and Week 8 (Predictions) activities of Columbia University's AI bootcamp