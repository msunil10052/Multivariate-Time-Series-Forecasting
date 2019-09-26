# Multivariate-Time-Series-Forecasting
This is the Repository for Machine Learning and Deep Learning Models for Multivariate Time Series Forecasting.The objective of case study is to compare various models with minimal feature engineering techniques.

Time series data is a series of data points **measured at consistent time intervals** which may be hourly, daily, weekly, every 10 days, and so on. In a time series data, each data point in the series depends on the previous data points.

In **multivariate, Time-Series** data, multiple variables will be varying over time. Each variable depends not only on its past values but also has some dependency on other variables. This dependency is used for forecasting future values. In univariate, Only one variable is varying over time.

Here we will address the problem using Classical Linear Models, Tree based algorithms, Ensemble Methods and Neural Network based Methods.

# Problem Statement
Your client is the city council of Paris, France. The council shared with you the data set and a data dictionary. The Paris city council leadership is interested in understanding the drivers behind the electricity consumption and are looking for data-driven recommendations for making policies on Effective usuage of electricity.

# Data Description
This dataset contains electric power consumption in one household with a one-minute sampling rate over a period of almost 4 years. It was obtained from the UCI archive (https://archive.ics.uci.edu). This archive contains 2075259 measurements gathered in a house located in Sceaux (7km of Paris, France) between December 2006 and November 2010 (47 months).

The data was originally published by 

Georges Hebrail (georges.hebrail '@' edf.fr), Senior Researcher, EDF R&D, Clamart, France
Alice Berard, TELECOM ParisTech Master of Engineering Internship at EDF R&D, Clamart, France

The are 9 attributes, they are:

1.date: Date in format dd/mm/yyyy
2.time: time in format hh:mm:ss
3.global_active_power: household global minute-averaged active power (in kilowatt)
4.global_reactive_power: household global minute-averaged reactive power (in kilowatt)
5.voltage: minute-averaged voltage (in volt)
6.global_intensity: household global minute-averaged current intensity (in ampere)
7.sub_metering_1: energy sub-metering No. 1 (in watt-hour of active energy). It corresponds to the kitchen, containing mainly a dishwasher, an oven and a microwave (hot plates are not electric but gas powered).
8.sub_metering_2: energy sub-metering No. 2 (in watt-hour of active energy). It corresponds to the laundry room, containing a washing-machine, a tumble-drier, a refrigerator and a light.
9.sub_metering_3: energy sub-metering No. 3 (in watt-hour of active energy). It corresponds to an electric water-heater and an air-conditioner.

# Modeling Methods:

Here the dataset is 

There are perhaps three classes of methods that might be interesting to explore on this problem; they are:

* Classical Linear Methods.
* Machine Learning Methods.
* Deep Learning Methods.

## Code

The solution is split into Exploratory data analysis and Model Building. 

Exploratory data analysis results are stored in below notebook.

1. `Exploratory data analysis.ipynb`

Below are the notebooks for Models:

1. `Machine Learning - Model 1.ipynb` for Non linear models
2. `Deep Learning - Model 1.ipyb` for Keras based linear regression
3. `Classical Linear Models.ipynb' for linear models

You need to have [Jupyter Notebook](http://ipython.org/notebook.html) installed to run the file

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

Before running the file, first install all necessary dependencies:

```
pip3 install -r requirements.txt
```

## Run

To run the notebook, open terminal or command window, navigate to the top-level project directory `Multivariate-Time-Series-Forecasting/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Exploratory data analysis.ipynb
```  
or
```bash
jupyter notebook Exploratory data analysis.ipynb
```




