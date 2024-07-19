## Portfolio_Manager_Project_1
# Git README Rubric

Documentation (10 points)
Code is well commented with concise, relevant notes (3 points).

GitHub README file includes a concise project overview (2 points).

GitHub README file includes detailed usage and installation instructions (2 points).

GitHub README includes either examples of the application, or the results and a summary of the analysis (3 points).

## Project Overview:

While working for a large equity-trading company, our team is tasked with researching our client’s portfolio. Our client has an interest in investing within the magnificent 7 tech companies, specifically Apple, Nvidia, Amazon  and Tesla and need expert analysis to invest and make the best-calculated decisions with data backing it up. In our example, we will be pulling data from NASDAQ (https://data.nasdaq.com/) and examining the last year of trading data. We will examine which stocks trended upwards, downwards, and which we recommend most by performing an extensive comparative analysis.

## Research Questions:

1) How do the returns of Nvidia, Tesla, Apple, and Amazon compare over  the past year?
2) What trends and volatility patterns do they follow?
3) What investment recommendations can be made on the comparative performance analysis?

## Statistical Analysis Techniques:

In order to manipulate, compare and contrast our data, we follow different statistical analysis techniques to discover patterns and findings. Then, we back up our observations with beautiful visuals to help communicate the message.

As our data was prepared, we focused on several statistical / time series analysis techniques and perspectives to help us solve our research questions.
1) Aggregation - Our first focus, calculating the average daily returns over the past year of each stock.
2) Correlation - Determining correlations between each stock and if they follow common trends.
3) Comparision - Comparing cumulutive returns over the past year.
4) Summary Statistics - Calculating summary statistics such as mean, standard deviation, percentiles for daily returns.

## Key Visualizations and Patterns
In order to understand and compare the selected stocks, we must focus on several research topics:
1) Calculating mean daily returns from the past year, for each stock, helps give the average performance and return, in which we can compare and further evaluate which stocks would be better in placing investment positions in, with different graph representations such as bar and line graphs.

![CUMULATIVE RETURNS ALL](https://github.com/user-attachments/assets/ef0dbe08-5afc-4dd3-8dcb-123c356686fa)

2) Calculating standard deviation of cumulative returns, as well as heatmap summaries of cumulative returns and  percentiles and mean returns.

![HEAT MAP CUMULATIVE RETURNS](https://github.com/user-attachments/assets/8bf0a0a9-5218-42d3-b873-9976dbabb44a)

3) Trendlines of closing prices for selected stocks, from the past year.
4) Comparing mean vs standard deviation of cumulative returns with plot graph visual.
5) Bollinger Bands showing market volatility and identifying overbought/oversold conditions.

## Conclusions & Observations

After collecting data on Nvidia, Apple, Amazon and Tesla, we have concluded to the following recommendations:
1) Nvidia should be the safest best, and largest position to be placed, out of all the chosen stocks due to highest daily returns across the past year, highest standard deviation, or market volatility in the positive direction, and strong positive trendlines of closing stocks, therefore, highest returns.
2) Amazon and Apple appear to be considered mid size positions, with smaller returns, weaker trendlines and market volatility than Nvidia, but also not the worst performing tech stock observed.
3) Investing in Tesla, should be the smallest position to be placed, out of all the chosen stock, due to lowest daily returns, and worst performing trend lines.
