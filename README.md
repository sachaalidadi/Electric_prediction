## About this repository

This repository contains a machine learning model that predicts the electricity production.

The training of this model can be found in the python notebook named `model_training.ipynb`

## About the notebook

The notebook contains two parts:

* EDA (Exploratory Data Analysis): Where we perform a statistical analysis of our dataset
* Model training: We select the relevant models for our problem and optimize the hyperparameters of the model

For this problem, we used autoregression models.

## About the dataset

The dataset is a .csv file containing the electricity production from 1985 to now.

## How to replicate the results

The dataset can be found in the repository under the name `Electric_production.csv`

To execute the notebook, you need Python 3 and the following libraries:

* matplotlib
* numpy
* pandas
* seaborn
* statsmodels

You can install these libraries using the following command:

```shell
pip install requirements.txt
```

requirements.txt is the txt file containing the names of the necessary libraries