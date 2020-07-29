# Chicago-Crime-Rate--Time-Series-Analysis
# Objective
The primary goal for this analysis is to use univariate and multivariate time series models to predict the crime rate in Chicago and examine the relationship between the crime rate and the unemployment rate. For this, SARIMA will be used to look at both subclasses of crime and the aggregate crime rate, as well as the unemployment rate. Then, Granger Causality will be used to establish a link between these different crime categories and unemployment. Afterward, a basic VAR will be carried out, followed up by a Two-Stage Model and sVARMA, in order to portray the relationship between crime and unemployment. The outcomes of these methods will be compared against basic Linear Regression in order to highlight the shortcomings of conventional regression and to demonstrate the importance of understanding how to analyze data using a temporal perspective.

![](Data/Unemployement.png)

# Data Source
Our data comes from 2 sources. The crime data is obtained from the Chicago Data Portal supported by the City of Chicago. It has an open-source dataset of Chicago crimes from 2001 to the present. It contains variables such as the date, type, and location of each crime reported on a daily basis.

https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present-Dashboard/5cd6-ry5g

The second data source is the Illinois Department of Statistics. It has monthly unemployment rates in each county. We use the Cook county Chicago Metropolitan Area data.

http://www.ides.illinois.gov/xxlmi/Pages/Local_Area_Unemployment_Statistics.aspx

# Tools
R, Python
