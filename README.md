# INSAID2021-ML-Advanced-Concrete_Compressive_Strength_Prediction
INSAID 2021 ML Advanced Term Project

# Project Description
## Introduction
Client for this project is a major Concrete Producer.

Their concrete stands out to be one of the best in the business and holds a contract with five of the most well known real estate companies.

Recently, they have developed a new kind of concrete which requires less water and is stronger and better than the concrete they used to sell.
They have few competitors who are also developing new kinds of concrete to launch in the market to get more clients.

## Current Scenario
The regular price of concrete per cubic yard is around $100 to $200 but due to market inflation the current price has gone down and the company is at loss.

The company has developed a new concrete solution which can be a potential game-changer for the company in the market but they are not sure about the concrete compressive strength which is a very important factor for concrete sale.

## Problem Statement
The current process suffers from the following problems:

 * The company is under a time crunch to test the compressive strength of the concrete to release in the market.
 * Previously they were using manual methods to test the compressive strength of the concrete which is very time-consuming and inefficient.

They want to automate the process of predicting the compressive strength of the concrete, based on the materials used.

## Project Task
* Dataset containing materials used in the concrete is provided.
* Project task is to build a regression model using the dataset.
## Project Deliverables
* Deliverable: Predict the compressive strength of concrete.
* Machine Learning Task: Regression
* Target Variable: csMPa
* Win Condition: N/A (best possible model)
## Evaluation Metric
* The model evaluation will be based on the RMSE score.
# Data Description
* The dataset contains materials used in making the concrete.
* The column csMPa is the compressive strength of concrete.
* This is the data that we have to predict the compressive strength.

The dataset is divided into two parts: Train and Test sets.

## Train Set:
* The train set contains 824 rows and 10 columns.
* The last column csMPa is the target variable.

## Test Set:
* The test set contains 206 rows and 9 columns.
* The test set doesn’t contain the csMPa column.
* It needs to be predicted for the test set.

# Dataset Feature Description
The Dataset contains the following columns:

| ID | Feature Name | Description of the feature |
| :-- | :--| :--| 
|01| **Id**   | Unique identity of each observation                          |
|02| **cement** | Quantity of cement in the mixture in kg(kilogram)                |
|03| **slag**        | Quantity of slag in the mixture in kg(kilogram)            |
|04| **Flyash**          | Quantity of fly ash in the mixture in kg(kilogram)                     |
|05| **water**      | Quantity of water in the mixture in kg(kilogram)                  |
|06| **superplasticizer**           | Quantity of superplasticizer in the mixture in kg(kilogram)
|07| **coarseaggregate**     | Quantity of coarse aggregate in the mixture in kg(kilogram) |
|08| **fineaggregate**     | Quantity of fine aggregate in the mixture in kg(kilogram)|
|09| **age**        | Age of the mixture in days|
|10| **csMPa**          | compressive strength of concrete in MPa(dependent variable) |
