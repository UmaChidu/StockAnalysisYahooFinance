# StockAnalysisYahooFinance
Stock Market Data from Yahoo finance collected everyday from 1965 to recent. Analyze and understand trends to invest.
Data was used from kaggle, reliable source. This is historic data for each index and was combined into one csv.
It containes data for indexes tracking stock exchanges from all over the world (United States, China, Canada, Germany, Japan and more).
Initial visual analysis was performed on python and its libraries. Correlation of each of the variables showed high postive correlation with each other.
Performed a geospatial analysis using geojson by creating a choropleth map. It showed the highest for US, Canada and Switzerland followed by India, China and Taiwan.
Scatter plot and after removing extreme values did a correlation to create linear regression of Open and High showing very high positive correlation.
Using machibe learning and k-means algorithm created a visual of adjustable close and Volume showing 10000 to 12500 USD having more volume.
Time series analysis was performed after grouping values of each month and building a dataframe with data for each month and only considering recent years begining of 2001. Shows the peak during year 2009 and 2021.
Dickey-Fuller Test for performed to test the stationarity of data and if it is ready for predictions. Differentiating operation performed to stationarize the data.
