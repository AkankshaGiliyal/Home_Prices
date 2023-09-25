# Home_Prices
Understanding Factors Influencing US Home Prices Over the Last 20 Years<br>

In this data analytics project, I aimed to uncover the key factors that have influenced home prices in the United States over the past two decades. The project leverages publicly available data from various sources, including the S&P Case-Schiller Home Price Index, and other economic indicators such as stock prices, consumer price index, population, unemployment rate, real GDP, mortgage rates, and real disposable income.<br>
Data Collection:
collected and cleaned two primary datasets: one containing the S&P Case-Schiller Home Price Index data and the other containing the key economic indicators. Both datasets include monthly data spanning over 20 years.

S&P Case-Schiller Home Price Index Data: This dataset provides information on the national home price index from 20 years ago until the present, allowing us to analyze long-term trends in home prices.

Key Economic Indicators Data: This dataset encompasses a range of key economic variables, such as stock prices, consumer price index, population, unemployment rate, real GDP, mortgage rates, and real disposable income. These factors were chosen based on their potential impact on the housing market.

Data Analysis:
Analysis involved merging these datasets based on the common date feature. However, since the datasets used different date formats, conducted data preprocessing was conducted to align the date formats and ensure compatibility for merging. Once merged, performed exploratory data analysis (EDA) to gain insights into the relationships between the key economic indicators and home prices.

Key Findings:

Correlation Analysis: Calculated correlations between the home price index and each of the key economic indicators. The analysis revealed notable correlations between home prices and factors such as stock prices, consumer price index, and mortgage rates.

Regression Analysis: To quantify the impact of these factors on home prices, conducted a linear regression analysis. The regression results showed the coefficients for each key factor, indicating their respective contributions to home price fluctuations.

Insights:

Stock Price Index and Consumer Price Index had positive coefficients, suggesting that increases in these factors were associated with higher home prices.
Mortgage rates had a significant positive coefficient, indicating that lower mortgage rates positively influenced home prices.
Unemployment rate had a negative coefficient, implying that lower unemployment rates were associated with higher home prices.
Model Performance:
The regression model exhibited a high R-squared value of 0.94, indicating that it explained a significant portion of the variance in home prices. The Mean Squared Error (MSE) was 192.70, suggesting that the model's predictions were close to the actual home prices.

Conclusion:
In conclusion, this project provides valuable insights into the factors influencing US home prices over the last 20 years. By analyzing key economic indicators and their correlations with home prices, we have identified the factors that have had the most significant impact on the housing market. This analysis can be valuable for homeowners, investors, and policymakers seeking to understand and predict trends in the real estate market.
