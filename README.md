# Analysis of Pattern and Trends on COVID-19 (Novel Coronavirus)

## Summary

<describe the purpose of this repository, the information it contains, and any relevant analysis goals. What, why, where, when, how?>

This repository was prepared for the final project of Env 872L course, Environmental Data Analytics at Duke Univeristy, Spring 2020.

* I will use covid-19 data to do analysis on China and other global countries, especailly Italy and the United States. 
* I will also  do time series anlysis and mapping covid-19 data on country and city levels. 

## Investigators

Xueying Feng, Duke University, xueying.feng@duke.edu.

## Keywords

COVID-19, time series, Geospatial analysis

## Database Information

I access all Novel Coronavirus data from the R package, nCov2019, which includes detailed real-time statistics, historical data in all countries, and down to the city-level.

*Tianzhi Wu, Erqiang Hu, Xijin Ge*, Guangchuang Yu*. Open-source analytics tools for studying the COVID-19 coronavirus outbreak. medRxiv, 2020.02.25.20027433. doi: https://doi.org/10.1101/2020.02.25.20027433*

## Folder structure, file formats, and naming conventions 

<describe the folders contained in the repository, including what type of files they contain>

<describe the formats of files for the various purposes contained in the repository>

<describe your file naming conventions>

Folders contained in the repository:
* Code (RMD file)
* Data (csv file)
* Output (pdf file)

## Metadata

Covid19_China.csv
| Column name | Description |
| --- | --- |
| name | Provivence name in China |
| nowConfirm | Increased number of COVID-19 cases in each province in China by date reported |
| confirm | Cumulative total number of COVID-19 cases in each province |
| dead | Total deaths number of COVID-19 cases in each province in China |
| deadRate | Total deaths number/ Cumulative total number of COVID-19 cases |
| heal | Total heal number of COVID-19 cases in each province |
| healRate | Total heal number/ Cumulative total number of COVID-19 cases |


Covid19_Hubei.csv
| Column name | Description |
| --- | --- |
| name | City name in Wuhan |
| nowConfirm | Increased number of COVID-19 cases in each city in Wuhan by date reported |
| confirm | Cumulative total number of COVID-19 cases in each city |
| dead | Total deaths number of COVID-19 cases in each city in Wuhan |
| deadRate | Total deaths number/ Cumulative total number of COVID-19 cases |
| heal | Total heal number of COVID-19 cases in each province |
| healRate | Total heal number/ Cumulative total number of COVID-19 cases |


Covid19_Global
| Column name | Description |
| --- | --- |
| name | Country name |
| confirm | Cumulative total number of COVID-19 cases in each country |
| dead | Total deaths number of COVID-19 cases in each country |
| deadRate | Total deaths number/ Cumulative total number of COVID-19 cases |
| heal | Total heal number of COVID-19 cases in each country |
| healRate | Total heal number/ Cumulative total number of COVID-19 cases |


Covid19_Italy
| Column name | Description |
| --- | --- |
| time | Recorded date for COVID-19 cases |
| country | Country name |
| province | Province name |
| cum_confirm | Cumulative total number of COVID-19 daily cases in each province |
| cum_heal | Total heal number of COVID-19 cases in daily each province |
| cum_dead | Total deaths number of COVID-19 cases in daily each province |


Covid19_US
| Column name | Description |
| --- | --- |
| time | Recorded date for COVID-19 cases |
| country | Country name |
| province | State name |
| cum_confirm | Cumulative total number of COVID-19 daily cases in each State |
| cum_heal | Total heal number of COVID-19 daily cases in each State |
| cum_dead | Total deaths number of COVID-19 daily cases in each State |


historical_China
| Column name | Description |
| --- | --- |
| time | Recorded date for COVID-19 cases |
| country | Country name |
| province | State name |
| city | City name in each province |
| cum_confirm | Cumulative total number of COVID-19 daily cases in each city |
| cum_heal | Total heal number of COVID-19 daily cases in each city |
| cum_dead | Total deaths number of COVID-19 daily cases in each city |


historical_Global
| Column name | Description |
| --- | --- |
| time | Recorded date for COVID-19 cases |
| country | Country name |
| cum_confirm | Cumulative total number of COVID-19 daily cases in each country |
| cum_heal | Total heal number of COVID-19 daily cases in each country |
| cum_dead | Total deaths number of COVID-19 daily cases in each country |

## Scripts and code

In code folder:
* Data Processing
* Data wrangling
* Data exploration (time series, mapping of global data, ect.)
* Data analysis

## Quality assurance/quality control

<describe any relevant QA/QC procedures taken with your data. Some ideas can be found here:>
<https://www.dataone.org/best-practices/develop-quality-assurance-and-quality-control-plan>
<https://www.dataone.org/best-practices/ensure-basic-quality-control>
<https://www.dataone.org/best-practices/communicate-data-quality>
<https://www.dataone.org/best-practices/identify-outliers>
<https://www.dataone.org/best-practices/identify-values-are-estimated>