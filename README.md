# EXPLORATORY DATA ANALYSIS ON MORTALITY IN NIGERIA AND ITS BORDERING COUNTRIES

## Table of Contents
- [Project Overview](project-overview)
- [Tools Used](tools-used)
- [Data Sources](data-sources)
- [Dataset](dataset)
- [Data Cleaning](data-cleaning)
- [Data Analysis](data-analysis)
- [Findings](findings)
- [Lessons](lessons)
- [Limitations](limitations)

## Project Overview
In this project, I explore the mortality in Nigeria, Benin, Chad, Cameroon, and Niger across 1970 to 2010. 

## Tool Used
- Microsoft Excel

## Data Sources:
- Internet. 
Disclaimer: The accuracy of the dataset/data source was not ascertained. This project is only meant to demonstrate data analysis skills, and should not be referenced for official or learning purposes.

## Dataset
[mortality project.xlsx](https://github.com/user-attachments/files/19115549/mortality.project.xlsx)

## Data Cleaning
For the purposes of this project, the dataset was already ready to be used without further cleaning.

## Data Analysis
### Using pivot tables and other Excel functionalities, these analyses were carried out:
- **Decades with maximum and minimum deaths in Nigeria:** I calculated this using the excel formulas below and linked it to text boxes in the dashboard
  
  ``` =INDEX(A5:A9,MATCH(MIN(B5:B9),B5:B9)) ```
  ``` =INDEX(A5:A9,MATCH(MAX(B5:B9),B5:B9)) ```

- Total deaths in Nigeria across the decades
- Total sum of death in Nigeria among males and females
- Total deaths per age group in Nigeria
- Total deaths in Nigeria and its bordering countries within the total timeframe captured by the dataset (1970--2010); also divied based on sex for each country
- Sum of death rates in each countries within the total timeframe; also divided based on sex for each country.

## Findings
- In Nigeria, from 1970 till 2010, there was a steady increase in the number of deaths.
- Number of deaths of both sexes in Nigeria were high; it was higher in males.
- Children aged between 1 and 4 years old died in more numbers than any other age groups.
- Nigeria had the highest number of deaths among it and its bordering countries, but when the death rate is observed, we find that the death rates across all five countries were quite close to each other, with Niger being the most burdened.

## Lessons
Here is an example of how statistics might lead us to the wrong conclusions. Looking only at the number of deaths, it seemed as if Nigeria performed so much worse than all its neighboring countries. But when the death rate per 100,000 is observed we see that Niger actually takes the lead with the other four countries closely behind. This is due to the fact that Nigeria's population is much larger than that of its neighboring countries.

## Limitations
The quality of the dataset is not assured and this project is only for practical purposes.
