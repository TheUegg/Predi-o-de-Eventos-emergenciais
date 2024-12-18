# README

## Overview
This repository provides an overview of a partial implementations used in my final project (TCC). The project focused on **predicting emergency events**, particularly those caused by floods, landslides, and other environmental phenomena, by integrating historical, meteorological, and geographical data.

The work aimed to leverage **machine learning models**, such as ARIMA, RNN and LSTM.

## Project Description
The project consisted of the following key components:

1. **Data Understanding and Preparation**:
   - Integration of multiple datasets, including:
     - Emergency occurrences from the Fire Department of Santa Catarina (2017-2021).
     - Meteorological data obtained from the INMET website.
     - Risk area maps from the Geological Survey of Brazil (SGB).
   - Data cleaning and feature engineering using Python libraries such as Pandas.

2. **Model Development**:
   - Development of predictive models, including ARIMA for time series analysis and (RNN and LSTM) for deep learning predictions.
   - Evaluation of models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE).

3. **Experiments**:
   - Analyzing the impact of enriching datasets with meteorological and risk area data on prediction accuracy.
   - Studying the geographic and temporal distribution of emergency occurrences.

4. **Visualization and Results**:
   - Creation of visualizations to represent predictions, emergency hotspots, and data trends.

## Privacy and Limitations
Due to **privacy concerns and legal restrictions**, some key files and portions of the code have not been included in this repository. These include:
- Raw datasets containing sensitive information about emergency occurrences.
- Detailed model implementation files and experimental configurations.
- Codes that had output showing the dataset, even if the code was used for data cleaning

Despite these omissions, this repository provides:
- Sample scripts illustrating data preparation and visualization processes.
- Project workflow and experimental setup.

## Technologies Used
- **Programming Language**: Python
- **Libraries and Tools**: Pandas, Shapefile, Matplot, Shapely, Contextily, Sklearn, Keras e Numpy
- **Datasets**: INMET (Meteorological data), Fire Department (Emergency occurrences), SGB (Risk areas)
- **Methodologies**: CRISP-DM, Data Mining, Machine Learning

## Disclaimer
This repository serves as an educational resource to demonstrate the general workflow of the project. It does not contain all the materials required to replicate the experiments, as certain data and code are excluded for privacy reasons.

For any questions or further information, feel free to contact me.

