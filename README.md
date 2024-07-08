# PROJECT-8__Covid-19-Cases-Prediction-Till-Mid-23

This repository contains scripts and notebooks for analyzing COVID-19 data using Python, focusing on data import, preparation, visualization, and forecasting using Facebook Prophet.

## Import Datasets

This section focuses on importing COVID-19 datasets from John Hopkins University via Kaggle. Typically, these datasets include daily or cumulative counts of COVID-19 cases, deaths, and recoveries across various countries and regions worldwide. Kaggle provides a convenient platform for accessing and downloading these datasets, often in CSV format, which contain essential information necessary for tracking the global pandemic.

## Data Preparation

Once the datasets are imported, the script preprocesses the data to aggregate global COVID-19 cases by country. This involves cleaning the data, handling missing values, and aggregating or summarizing the data at the country level. Preprocessing might also include merging different datasets if additional information, such as population data or healthcare indices, is required. The goal is to prepare a clean and structured dataset that is suitable for visualization and analysis.

## Data Visualization

This step utilizes Plotly Express, a powerful Python library for creating interactive visualizations, to generate choropleth maps. These maps visually represent COVID-19 cases globally, categorized by case ranges (e.g., low, medium, high). Each country is shaded according to its respective COVID-19 case count, providing an intuitive way to understand the geographical distribution and severity of the pandemic across different regions.

## Data Visualization

In this section, the script plots daily COVID-19 cases and deaths globally over time. It often includes a 5-day moving average to smooth out daily fluctuations and highlight underlying trends. Visualizing daily trends helps identify spikes or declines in cases and deaths, enabling stakeholders to assess the effectiveness of public health interventions and track the progression of the pandemic on a global scale.

## Prediction for Next 30 Days

Using Facebook Prophet, a forecasting tool for time series data, this section forecasts COVID-19 cases for the next 30 days. Time series forecasting is crucial for anticipating future trends and planning resource allocation and response strategies. Facebook Prophet uses historical data on COVID-19 cases and deaths to generate predictions, taking into account seasonality, trends, and other factors that influence the spread of the virus.

## Dependencies

- pandas
- numpy
- matplotlib
- plotly.express
- prophet
- sklearn

## Clone the repository:
```bash
 git clone https://github.com/ishan-1010/PROJECT-8__Covid-19-Cases-Prediction-Till-Mid-23.git
