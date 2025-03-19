# Exploratory Data Analysis on Mortality in Nigeria and Its Bordering Countries

## Table of Contents
- [Project Overview](#project-overview)
- [Tools Used](#tools-used)
- [Data Sources](#data-sources)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Lessons](#lessons)
- [Limitations](#limitations)

## Project Overview
In this project, I explore the mortality in Nigeria, Benin, Chad, Cameroon, and Niger from 1970 to 2010. The analysis aims to uncover trends and insights into mortality rates across these countries.

![Mortality Chart](https://github.com/user-attachments/assets/45e199d1-9267-4930-9b5e-d215605d34b2)

## Tools Used
- Microsoft Excel

## Data Sources
- Internet source (Disclaimer: The accuracy of the dataset/data source was not ascertained. This project is only meant to demonstrate data analysis skills and should not be referenced for official or learning purposes.)

## Dataset
The dataset can be accessed [here](https://github.com/user-attachments/files/19115549/mortality.project.xlsx).

## Data Cleaning
For the purposes of this project, the dataset was already ready to be used without further cleaning.

## Data Analysis
### Using pivot tables and other Excel functionalities, the following analyses were carried out:
- **Decades with Maximum and Minimum Deaths in Nigeria:** 
  Calculated using the Excel formulas below and linked to text boxes in the dashboard:
  ```excel
  =INDEX(A5:A9,MATCH(MIN(B5:B9),B5:B9))
  =INDEX(A5:A9,MATCH(MAX(B5:B9),B5:B9))
  ```
- Total deaths in Nigeria across the decades
- Total deaths in Nigeria among males and females
- Total deaths per age group in Nigeria
- Total deaths in Nigeria and its bordering countries within the total timeframe captured by the dataset (1970--2010); also divided based on sex for each country
- Sum of death rates in each country within the total timeframe; also divided based on sex for each country

## Findings
- **Steady Increase in Deaths:** In Nigeria, from 1970 till 2010, there was a steady increase in the number of deaths.
- **Higher Male Mortality:** The number of deaths among both sexes in Nigeria were high, but higher in males.
- **Children Most Affected:** Children aged between 1 and 4 years old died in more numbers than any other age group.
- **Comparative Mortality Rates:** Nigeria had the highest number of deaths among it and its bordering countries, but when the death rate is observed, the death rates across all five countries were quite close, with Niger being the most burdened.

## Lessons
Statistics can be misleading if not analyzed correctly. Initially, it seemed Nigeria performed much worse than its neighboring countries based on the number of deaths. However, when considering the death rate per 100,000 population, Niger had the highest burden, highlighting the importance of context in data analysis.

## Limitations
The quality of the dataset is not assured, and this project is for practical purposes only.
