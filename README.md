# COVID-19 in South Korea
This repository is for the COVID-19 in South Korea mapping project for "Data Science for Public Health 1" at Johns Hopkins Bloomberg School of Public Health. 

# COVID-19 South Korea App
 https://taeeun-kwon.shinyapps.io/covid19_SouthKorea/

We have two sections in our app. The first section is an interactive map which shows all COVID-19 testing centers in South Korea, and the second section is the statistics of cumulative, daily and released cases in South Korea from January to current time. 

## 1. Covid-19 Testing Center Map 
* Data source
  
 We have two sections in our app. The first section is an interactive map which shows all testing centers in South Korea. The data were scrapped from Korean [Ministry of Health and Welfare](https://www.mohw.go.kr/react/popup_200128_2.html?fbclid=IwAR0naRh5ksc0Vj7HUOboJmf1WLRx2EKV6YnNs_5ns4MJ6YQ2-JzyVwEHNA0). We added the GPS data (latitude and longitude) of each testing center based on google map. We color-coded the testing centers according to COVID-19 testing availability and also included detailed information of each testing center. 

## 2. Statistics 
* Data source

 The data were extracted from [DS4C (Data Science for COVID19)](https://github.com/jihoo-kim/Data-Science-for-COVID-19) and edited with additional data from [Korea Center for Disease Control and Prevention(KCDC)](https://www.cdc.go.kr/cdc_eng/).
  
# Team Members and Role

*Taeeun Kwon (Johns Hopkins Bloomberg School of Public Health)* : Collecting COVID-19 testing centers data, Designing and Coding for the interactive map of COVID-19 testing centers and overall dashboard.

*Shudi Pan (Johns Hopkins Bloomberg School of Public Health)* : Coding for the basic structure of the interactive map of COVID-19 testing centers as well as further improvements. 

*Yunjeong Kim (Johns Hopkins Bloomberg School of Public Health)* : Collecting COVID-19 case data, Designing the overall structure of the Statistic Page, Coding for visualization of COVID-19 statistics (including plotting and mapping) in the statistic page.

# Acknowledgements
Thanks sincerely to *JunYoung Kim (University of Nevada Las Vegas, DataX Lab)* for his contribution to data collection.

# Disclaimer 

This is an assignment of Johns Hopkins Data Science for Public Health

