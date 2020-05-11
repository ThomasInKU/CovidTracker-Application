# Covid19 Tracker
## Introduction
Covid 19 tracker Application gives you real time Covid-19 disease data of more than 200 countries since 2020-1-1 as follows :
Total confirmed cases 
New confirm cases 
New deaths
Total deaths 
This project focuses on updating real time Covid-19 disease data from online sources and learns how to create a good GUI interface from JavaFX.

## Main Features

- Get real time Covid19 disease data.
- Create historical line graphs of Covid19 disease data.
- Get Covid19 information ;  total confirm cases, new confirm cases, new deaths and total deaths.


## How to run?

First you need to open **command prompt (for Windows)** or **terminal (for OSX)** and access CovidTracker.jar directory.

**for java sdk 8 type this command:**
> java -jar Covid19-Tracker.jar

**java sdk 11 or higher:**

> java --module-path (you javafx lib directory) --add-modules javafx.controls,javafx.fxml -jar Covid19-Tracker.jar

**Example:**

>java --module-path /Users/admin/Downloads/javafx-sdk-11.0.2/lib/ --add-modules javafx.controls,javafx.fxml -jar Covid19-Tracker.jar

## Credit
[Coronavirus source data](https://ourworldindata.org/coronavirus-source-data)

The updated .csv files here:
- [Total confirmed cases](https://covid.ourworldindata.org/data/ecdc/total_cases.csv)
- [Total deaths](https://covid.ourworldindata.org/data/ecdc/total_deaths.csv)
- [New confirmed cases](https://covid.ourworldindata.org/data/ecdc/new_cases.csv)
- [New deaths](https://covid.ourworldindata.org/data/ecdc/new_deaths.csv)




