# Exploratory Data Analysis (EDA) Project Using Python
## Table Contents 
 - [Project Overview](#project-overview)
    - [Specific Objectives](#specific-objectives)
 - [Data Sources](#data-sources)
 - [Tools](#tools)
 - [Data Cleaning ](#data-cleaning)
 - [Explaratory Data Analysis (EDA)](#explaratory-data-analysis)
 - [Data Analysis](#data-analysis)
 - [Results /Findings](#results/findings)
 - [Recommendations](#recommendations)
 - [Limitations](#limitations)
 - [References](#references)


### Project Overview
 This exploratory data analysis(EDA) project focuse on providing insights, trend, and overall overbiew of how Canada interact with refugees and asylum seekers from different countries from year 2012 - 2022. By analyzing this data thw concerned body will get rich insights about from which countries the Canada admitted highest number of refugees, total number of resettled refugees in Canada per year, and general trends in refugees and asylum seekers in Canada for the span of year 2012 upto 2022. 

 ## Specific Objectives 
 This EDA project will aims to answer the following basic five questions:
 1. From which countries has **Canada** admitted highest number of refugees?
 2. What are the total number of resettled refugees in Canada per year?
 3. What are the countries of origin for majority of asylum seekers made in Canada?
 4. What are the total number of asylum seekers claims made in Canada every year?
 5. What are the general trends in refugees and asylum seekers statistics from 2012 - 2022?


### Data Sources
UNHCR refugees data. This datasets was collected by UNHCR for refugees related for Canada between year 2012 - 2022. The primary datasets used in the EDA was 'UNHCR_refugees_data_for_Canada_2012_to_2022.csv', containing the detailed information about the datasets. [Download the datasets] ().
The original datasets was found in this UNHCR website [unhcr.org](https://www.unhcr.org/refugee-statistics/download/?url=8tIY7I) 

### Tools
Python was used in this exploratory data analysis(EDA) on UNHCR refugees data for Canada to clean the datasets, to manipulate the data and fot visualization. To download the python software [click here](https://www.python.org/downloads/)

### Data Cleaning 
In the intial stages of data analysis we have checked the data and perform the following tasks:
- Load data and inspect for the data dimensions, data types, check for missing values.

### Explaratory Data Analysis (EDA)
EDA was employed to answer all above 5 questions in the project.
-  To know from which countires that Canada admitted highest number of refugees.
-  To know total number of resettled refugees in Canada per year.
-  To know the countries of origin for majority of asylum seekers made in Canada.
-  To know the total number of asylum seekers claims made in Canada every year
-  To know the general trends in refugees and asylum seekers statistics from 2012 - 2022.

Overall, barplot and line graph was used in the EDA project.
### Data Analysis
In this EDA project we analyzed the datasets using Python:

```#1.From which countries has Canada admitted highest number of refugees?
df.groupby('Country-of-origin')['UNHCR-refugees'].sum().sort_values(ascending = False).head(10)
```

### Results /Findings

### Recommendations

### Limitations

### References

