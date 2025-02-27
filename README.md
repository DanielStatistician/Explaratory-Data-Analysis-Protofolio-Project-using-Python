# Exploratory Data Analysis (EDA) Project Using Python
## Table Contents 
 - [Project Overview](#project-overview)
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
---
 This exploratory data analysis(EDA) project focuse on providing insights, trend, and overall overbiew of how Canada interact with refugees and asylum seekers from different countries from year 2012 - 2022. By analyzing this data thw concerned body will get rich insights about from which countries the Canada admitted highest number of refugees, total number of resettled refugees in Canada per year, and general trends in refugees and asylum seekers in Canada for the span of year 2012 upto 2022. 

 ## Specific Objectives 
 This EDA project will aims to answer the following basic five questions:
 1. From which countries has **Canada** admitted highest number of refugees?
 2. What are the total number of resettled refugees in Canada per year?
 3. What are the countries of origin for majority of asylum seekers made in Canada?
 4. What are the total number of asylum seekers claims made in Canada every year?
 5. What are the general trends in refugees and asylum seekers statistics from 2012 - 2022?


### Data Sources
UNHCR refugees data. This datasets was collected by UNHCR for refugees related for Canada between year 2012 - 2022. The primary datasets used in the EDA was 'UNHCR_refugees_data_for_Canada_2012_to_2022.csv', containing the detailed information about the datasets.
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
In this EDA project we analyzed the datasets using Python. Some of the analysis we conducted include the followings:

To answer the first objective of the EDA project, we analyzed in the folowing ways and Canada was admitted highest number of refugees from Colombia in the span of 2012 upto 2022.
```
# From which countries has Canada admitted highest number of refugees?
df.groupby('Country-of-origin')['UNHCR-refugees'].sum().sort_values(ascending = False).head(10)

Output:

Country-of-origin
Colombia                  108416
China                      98586
Ukraine                    88376
Pakistan                   74737
Haiti                      70956
Sri Lanka                  66343
Nigeria                    60554
Mexico                     51072
Türkiye                    42533
Iran (Islamic Rep. of)     40881
Name: UNHCR-refugees, dtype: int64
```

### Results /Findings
The results of this EDA project was summarized as the followings:
1. Canada has predominantly admitted refugees from Colombia.
2. The total number of resettled refugees in Canada has varied over the years, reaching a peak of 163,751 in 2012 and fluctuating annually, with 140,621 resettlements in 2022.
3. The majority of asylum seekers in Canada predominantly come from Nigeria, with other significant countries of origin being India, Mexico, Haiti, and Colombia.
4. The total number of asylum seeker claims in Canada has seen substantial variations, with a notable increase in 2017 and a peak of 113,066 claims in 2022.
5. The general trends in refugees and asylum seekers statistics from 2012 to 2022 reveal dynamic patterns, reflecting changes in global circumstances and geopolitical events
  influencing migration to Canada

### Recommendations
Based on the following analysis, we recommend the following:
- Given that Colombia is the predominant source of refugees, Canada could explore targeted support programs to address the root causes of displacement in Colombia.
- Collaborative efforts with international organizations and diplomatic initiatives may contribute to stability and reduce the need for individuals to seek refuge.
### Limitations
The limitations of this exploratory data analysis (EDA) project lie in its exclusive focus on refugees and asylum seekers in Canada from 2012 to 2022. Consequently, other data analysts or researchers may want to explore additional insights pertaining to refugees in other countries as well.
### References
- UNHCR, the UN Refugee Agency(https://www.unhcr.org/)https://www.unhcr.org/R)
  
