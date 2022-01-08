# AQI_2016-2020_China

This is a data analysis report for AQI (air quality index) in 2016-2020 of China.

#### -- Project Status: Completed

## Project Objective

The purpose of this project is to complete a course final project, but it may give inspiration to analyzing spatiotemporal database.

### Methods Used

* Data Visualization
* Linear regression
* Nadayara-Waston kernel regression
* KNN
* etc.

### Technologies

* Python, jupyter
* Pandas
* Geopandas
* etc. 

## Project Description

* The data come from [CnOpenData](https://www.cnopendata.com/data/air-quality).
* I try to find out whether time or space influence the AQI, and if they do, how can we build a model to predict AQI considering both time and space factors.
* For the visualization part, I used time series and geopandas to give both time and space perspective.
* For the analysis part, I made a model myself. Basically, it was Nadayara-Waston kernel regression + linear regression to year + KNN to specify geographic information.
* The dataset is too large, and my jupyter is breaking down all the time. This blocks me handle better methods.

## Needs of this project

- know something about Nadayara-Waston kernel regression
- spend some time installing geopandas
- familiar with pandas

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).

2. Raw Data is being kept [here](https://github.com/Inherit-South/AQI_2016-2020_China/tree/main/data).

3. Data processing/transformation scripts are being kept [here](https://github.com/Inherit-South/AQI_2016-2020_China/blob/main/code.ipynb)

4. Environment and packages:

   * Python 3.8.8

   * numpy 1.20.1

   * pandas 1.2.4

   * plotnine 0.8.0+25.ga8ac7a3

   * matplotlib 3.3.4

   * seaborn 0.11.1

   * geopandas 0.10.2

   * scipy 1.7.3

   * sklearn 1.0.2

   * tqdm 4.62.3

5. I did the two geographic visualization under the geopandas environment. Except them, I completed all other codes under the base environment.
