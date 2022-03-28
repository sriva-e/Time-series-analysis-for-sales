# Time-series-analysis-for-sales
In this notebook I have done time series analysis on UK Ecommerce Dataset.

Firstly, I will only be considering UK's data out of other countries dats points, which turned out to be 495478 data points
after that I tried to find outliers in the given datset by doing some data preprocessing, I also invistaged plotted the outliers to get a visual representation of my data and afer that I cleaned the data. 

I also plotted out monthly sales to see which months had highest and which moths had lowest sales and presented my finding in the notebook. Plotted out scatter plots for time series of monthly data and made autocorrelation plots . Here my time series wasn't that great because I had very few data points.

So I decided instead of monthly data points I will be taking daily data points to make my time series and autocorrelation plots . After this I investigated the trend for daily sales data , which turned out to be positive trend. 

I also performed ARIMA regression, where I plotted out the fit of my predictions with actual data , Here I feel that I should have had more testing data to acheive a better prediction . 

After doing Monthly and daily analysis, I tried to do weekly analysis of sales data and found some interesting findings such as , the retailer is closed on saturday as there is no sales data for saturday!

Towards the end og the notebook I again tried to do time series analysis of daily sales data but with a different method. 

For fun, I also wanted to see what was the most popular product of this retailer and found out that it was T-light Holder!

Lastly , some conclusions that I drew were: 
From our daily, monthly and weekly analysis , we found out that around holidays stores in UK have highest increase in revenue, so we can stock up on popular products and increase the prices to generate more revenue. Moreover the stores can send out promotional offers on Sunday or Wednesday as the days where people seem to shop the most are Tuesday and Thursday.





