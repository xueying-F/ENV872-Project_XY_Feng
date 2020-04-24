# Analysis of Pattern and Trends on COVID-19 (Novel Coronavirus)

## Summary

This repository was prepared for the final project of Env 872L course, Environmental Data Analytics at Duke Univeristy, Spring 2020.

* I will use covid-19 data to do analysis on global level, especailly China and the United States. 
* I will do the trend anlysis and mapp covid-19 data. 


## Investigators

Xueying Feng, Duke University, xueying.feng@duke.edu.

## Keywords

COVID-19, Trend anlysis, Geospatial analysis

## Database Information

I access all Novel Coronavirus data from the R package, nCov2019, which includes detailed real-time statistics, historical data in all countries, and down to the city-level.

*Tianzhi Wu, Erqiang Hu, Xijin Ge*, Guangchuang Yu*. Open-source analytics tools for studying the COVID-19 coronavirus outbreak. medRxiv, 2020.02.25.20027433. doi: https://doi.org/10.1101/2020.02.25.20027433*

## Folder structure, file formats, and naming conventions 

Folders contained in the repository:
* Code (RMD file)
* Data (csv file)
* Output (pdf file)

* All scripts are saved as .rmd format. 
* All scripts will be knitted and saved as a PDF when they are done.
* Both processed and raw data are saved as csv files.
* All outputs are saved as PDF files

## Metadata
Covid19_Global
| Column name | Description |
| --- | --- |
| name | Country name |
| confirm | Number of COVID-19 confirmed cases |
| dead | Number of COVID-19 death cases |
| deadRate | Total death number/ Cumulative total number of COVID-19 cases(%)|
| heal | number of COVID-19 heal cases |
| healRate | Total heal number/ Cumulative total number of COVID-19 cases(%)|


Covid19_China
| Column name | Description |
| --- | --- |
| name | Province name |
| confirm | Number of COVID-19 confirmed cases |
| dead | Number of COVID-19 death cases |
| deadRate | Total death number/ Cumulative total number of COVID-19 cases(%)|
| heal | number of COVID-19 heal cases |
| healRate | Total heal number/ Cumulative total number of COVID-19 cases(%)|


Covid19_US
| Column name | Description |
| --- | --- |
| time | Date |
| country | United States |
| province | States name |
| cum_confirm | Cumulative number of COVID-19 confirmed cases  |
| cum_heal | Cumulative number of COVID-19 heal cases |
| cum_dead | Cumulative number of COVID-19 death cases |


historical_China
| Column name | Description |
| --- | --- |
| time | Date |
| country | Country name |
| province | Province name |
| city | City name |
| cum_confirm | Cumulative number of COVID-19 confirmed cases  |
| cum_heal | Cumulative number of COVID-19 heal cases |
| cum_dead | Cumulative number of COVID-19 death cases |

historical_Global
| Column name | Description |
| --- | --- |
| time | Date |
| country | Country name |
| cum_confirm | Cumulative number of COVID-19 confirmed cases  |
| cum_heal | Cumulative number of COVID-19 heal cases |
| cum_dead | Cumulative number of COVID-19 death cases |


## Scripts and code

In code folder:
* Data Processing - Script for downloading data from R package and save as raw data
* Data wrangling - Script for importing raw dataset and making data neat for analysis and save as processed data.
* Data exploration - Script for exploring data, such time series, mapping of global data, ect.
* Data analysis -  Script for all analysis.
