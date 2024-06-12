# WalmartMLE

## Introduction

WalmartMLE is a project aimed at developing a machine learning pipeline for analyzing and forecasting sales data from Walmart stores. The goal is to scale up the model training pipeline to run in parallel utilizing multiple cores on a computer.

## Installation
 pip install -r requirements.txt

## Usage

1. Clone the repository to your local machine.
2. Ensure that the necessary data files (calendar.csv, sales_train_validation.csv, sell_prices.csv) are located in the data folder according to the provided Folder Structure.png.
3. Run the main script to execute the machine learning pipeline and generate forecasts.

## Features

1. Scaled up the model training pipeline to run in parallel utilizing multiple cores on a computer using MirroredStrategy.
2. Reorganized the code to ease pipeline definition.
3. Created a custom pipeline using Sklearn Pipeline.
   ![image](https://github.com/isthatdebbiej/WalmartMLE/assets/6524599/47065bc4-e227-496c-a7db-e2dbacd962f5)


## Documentation

- [MirroredStrategy](https://www.tensorflow.org/api_docs/python/tf/distribute/MirroredStrategy)

## Author

Deborah Shekinah Jacob
