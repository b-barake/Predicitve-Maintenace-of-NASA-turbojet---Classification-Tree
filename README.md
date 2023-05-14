# Predicitve-Maintenace-of-NASA-turbojet---Classification-Tree
Welcome to the Predictive Maintenance project for NASA Turbofan Engines. This project was developed with the aim of improving upon previous models to predict aircraft engine failures and to optimize maintenance schedules. Unlike its predecessor, which utilized an LSTM approach, this project employs a Decision Tree Classification Model to predict the remaining useful life of aircraft engines.

## Dataset Overview

The dataset, sourced from Kaggle, comprises sensor readings from a fleet of simulated aircraft gas turbine engines operating under different conditions. This data, represented as multiple multivariate time series, is split into two main parts: the training set and the test set.

- Training Set: Each row in this dataset represents a snapshot of data taken during a single operational cycle, with each column representing a different variable or sensor reading.

- Test Set: Similar to the training set but with a twist: the measurements for each engine are truncated at a certain point in time before the engine fails. This unknown time point is contained in a separate truth dataset.

Through these datasets, we simulate the real-world scenario of monitoring an engine's health over time and predicting an upcoming failure.

## Model Overview

This project implements a Decision Tree Classification Model, chosen for its ability to effectively handle both categorical and numerical data and its interpretability. The model uses the sensor readings to predict when an engine might fail in the future, allowing for maintenance to be planned and scheduled proactively.

## Inspiration and Objective

This project was inspired by the Predictive Maintenance using LSTM project found on Kaggle. While the previous project used LSTM (Long Short-Term Memory) models to predict the remaining useful life (RUL) of engines, our project differs in that we use a Decision Tree Classification model.

The ultimate goal of this project is to provide a more robust and reliable tool that can aid in aircraft engine maintenance. By accurately predicting the remaining useful life of an engine, we aim to prevent unexpected failures, improve safety, and streamline the maintenance scheduling process. This model can prove beneficial to maintenance teams, aircraft manufacturers, and airlines by allowing them to preemptively address potential engine issues and maintain optimal performance of their fleets.
