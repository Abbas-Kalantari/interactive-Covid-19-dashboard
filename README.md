
### Software Heritage
[![SWH](https://archive.softwareheritage.org/badge/swh:1:dir:a6c5dd6e0cb40fdb352b8f9da8e9ff47e7f31a0a/)](https://archive.softwareheritage.org/swh:1:dir:a6c5dd6e0cb40fdb352b8f9da8e9ff47e7f31a0a;origin=https://github.com/Abbas-Kalantari/interactive-Covid-19-dashboard;visit=swh:1:snp:bc4861bb86c333924c4d6e30dd96d6ce5e505d21;anchor=swh:1:rev:2b6eb24dc710b4d421502723a296fbe407b78e09)

# INTERACTIVE COVID19 DASHBOARD
![image](https://user-images.githubusercontent.com/72027409/121660016-2853e980-caa3-11eb-936f-8d29e47b54bf.png)
Source: Centers for Disease Control and Prevention’s Public Health Image Library 

This project is performed by the CRI Digital Science Students at Paris/France. The dashboard will visualize the Covid-19 Situation in All Countries Coronavirus disease (COVID-19) is an infectious disease caused by a newly discovered coronavirus. Most people infected with the COVID-19 virus will experience mild to moderate respiratory illness and recover without requiring special treatment.we would like analyze current situation of Covid on the world.

Our open-source data taken from the links below:

https://www.kaggle.com/antgoldbloom/covid19-data-from-john-hopkins-university
https://covid.ourworldindata.org/data/owid-covid-data.csv

## Streamlit Online
You can access the dashboard through this link:

https://thawing-anchorage-53534.herokuapp.com/

## Key to Dataset 

The covid dataset has the following fields:
Main Variables in Both Datasets

 | Variable  | Definition  |
 | ---  | ---  |
 | Date | The date of the summary |  
 | Province | The province or state, when applicable |
 | Country | The country or region name |
 | Lat | Latitude point |
 | Long | Longitude point |
 | Type | The type of case (i.e., confirmed, death) |
 | Cases | The number of daily cases (corresponding to the case type) | 
 | Continent | continent where cases occur |
 | New cases | Number of new cases |
 | Fatalities | Risk of death |
 | Total Deaths |Cumulative number of deaths  |
 | Total Cases | The cumulative number of cases |

## Dependencies
**All the requirements needed for this projects is stored in the [requirement.txt](https://github.com/Abbas-Kalantari/interactive-Covid-19-dashboard/blob/master/requirements.txt) file.**

*to run it on your local computer follow the guideline below:*

#### 1. cloning the repo

```bash

git clone https://github.com/Abbas-Kalantari/interactive-Covid-19-dashboard

```
#### 2. go to the folder

```bash

cd interactive-Covid-19-dashboard

```
#### 3. installing requirements

```bash

pip install requirements.txt

```
#### 4. Enjoy :)

```bash

streamlit run covid_app.py

```

## Dashboard

A supporting dashboard is available [here](https://thawing-anchorage-53534.herokuapp.com/)


