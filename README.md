# Energy-Anomaly-Detection-Up
This project involves detecting anomalies in energy consumption data using advanced machine learning techniques, specifically Long Short-Term Memory (LSTM) networks and Autoencoders. The project encompasses data preprocessing, exploratory data analysis, model training, evaluation, and anomaly detection.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction
Energy consumption patterns can provide valuable insights into operational efficiency and potential issues within a system. This project aims to identify anomalies in energy usage, which could indicate unusual or unexpected behavior. We leverage LSTM networks and Autoencoders to detect these anomalies, offering a robust approach to monitoring and managing energy consumption.

## Project Structure
The project is organized as follows:
- `notebooks/`: Jupyter notebooks containing the analysis and model training.
- `data/`: Directory to store the dataset.
- `models/`: Directory to save trained models.
- `plots/`: Directory to save generated plots and visualizations.
- `README.md`: Project documentation.

## Dataset
The dataset used in this project is the [Energy Consumption Dataset](https://archive.ics.uci.edu/ml/datasets/Energy+consumption+dataset) from the UCI Machine Learning Repository. It includes various features related to energy consumption and environmental conditions.

### Data Fields
- `date`: Date and time of the observation.
- `Appliances`: Energy consumption in Wh.
- `lights`: Energy consumption of light fixtures.
- `T1` to `T9`: Temperature measurements from various rooms.
- `RH_1` to `RH_9`: Humidity measurements from various rooms.
- `T_out`: Outside temperature.
- `Press_mm_hg`: Outside atmospheric pressure.
- `RH_out`: Outside humidity.
- `Windspeed`: Outside wind speed.
- `Visibility`: Outside visibility.
- `Tdewpoint`: Outside dew point temperature.
- `rv1` and `rv2`: Random variables for validation purposes.

## Installation
To run this project, you need to have Python installed along with the following libraries:

```bash
pip install numpy pandas scikit-learn keras matplotlib seaborn plotly
