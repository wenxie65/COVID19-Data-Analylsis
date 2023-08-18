# COVID19 Data Analylsis
This repository contains date reted to the COVID-19 pandemic in the United States. The data is soruced from [COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19/).

## Data Source
The data used for this analysis came directly from the JHU CSSE repository. The specific datasets being used are [time_series_covid19_confirmed_US.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_US.csv) and [time_series_covid19_deaths_US.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_US.csv) filesm which contains the time-series data of COVID-19 cases.

## Data Preparation
In Tableau, the data was manipulated to pivot the dates columns and obtain a date column and a cases column. This transformation makes it easier to analyze and visulaize how COVID-19 cases change over time.

## Analysis
The analysis in this project covers several areas:
- Trend analysis of confirmed and death cases over time.
- State-wise comparison of cases for the years 2020 to 2023.
- Caluculation and visualization of the mortality rate.

## Visualizations
This Tableau project aims to provide insights into the progression and impacts of the COVID-19 pandemic across various regions over a span of three years. The visualizations offer a comprehensive understanding of the effects of the pandemic.
1. **Compraison Line Graph ([Confirmed and Death Cases Over Time](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Cases%20vs.%20Date.png)):** The comparison line graph illustrates the trend in confirmed and death cases over time from January 2020 to March 2023.
2. **[Mortality Rate Over Time](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Mortality%20Rate%20vs.%20Date.png):** The graph illustrates the changes in the mortality rate from January 2020 to March 2023.
3. **Comparison Bar Graph ([Confirmed Cases and Deaths in 2020](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Cases%20vs.%20State%202020.png)):** The bar graphs compare the numbers of confirmed COVID-19 cases and deaths across various states and territories in the year 2020.
4. **Comparison Bar Graph ([Confirmed Cases and Deaths in 2021](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Cases%20vs.%20State%202021.png)):** The comparison bar graph illustrates the count of COVID-19 cases and deaths in various states and territories during the year 2021.
5. **Comparison Bar Graph ([Confirmed Cases and Deaths in 2022](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Cases%20vs.%20State%202022.png)):** The comparison bar graph shows the COVID-19 statistics for the year 2022 across different states and territories.
6. **Comparison Bar Graph ([Confirmed Cases and Deaths in 2023](https://github.com/wenxie65/COVID19-Data-Analylsis/blob/main/visualizations/Cases%20vs.%20State%202023.png)):** The comparison bar graph shows the COVID-19 statistics for the year 2023 across various states and territories.
