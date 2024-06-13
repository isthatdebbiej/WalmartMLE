# WalmartMLE

## Introduction

The goal is to scale up the model training pipeline to run in parallel utilizing multiple cores on a computer. The model has been developed by the data Scientists at Walmart for the M5 competition posted on Kaggle.

## Installation
 pip install -r requirements.txt

## Usage

1. Clone the repository to your local machine.
2. Ensure that the necessary data files (calendar.csv, sales_train_validation.csv, sell_prices.csv) are in the data folder according to the provided Folder Structure.png.
3. Run the main script to execute the machine learning pipeline and generate forecasts.

## Features

1. Scaled up the model training pipeline to run in parallel utilizing multiple cores on a computer using MirroredStrategy. Here, we are using all the GPUs available for synchronous training across multiple replicas on one machine.![image](https://github.com/isthatdebbiej/WalmartMLE/assets/6524599/0925d6e9-6c88-40c6-a15d-4ba400eca640)
2. Reorganized the code to ease pipeline definition.
3. Created a custom pipeline using Sklearn Pipeline.


   ![image](https://github.com/isthatdebbiej/WalmartMLE/assets/6524599/47065bc4-e227-496c-a7db-e2dbacd962f5)

## Documentation

- [MirroredStrategy](https://www.tensorflow.org/api_docs/python/tf/distribute/MirroredStrategy)
- [Customizing Scikit-Learn Pipelines](https://towardsdatascience.com/customizing-scikit-learn-pipelines-write-your-own-transformer-fdaaefc5e5d7)
- [Kaggle M5 Forecasting](https://www.kaggle.com/competitions/m5-forecasting-accuracy)
  


## Author

Deborah Shekinah Jacob
