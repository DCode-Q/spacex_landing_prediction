# SpaceX Falcon 9 Landing Prediction

This repository contains a data science capstone project developed as part
of the IBM Data Science Professional Certificate.

The project analyzes SpaceX Falcon 9 launch data and builds classification
models to predict whether the first stage of the rocket will successfully
land after launch.

## Project Goal

The goal of this project is to apply a complete data science workflow to a
real-world dataset:

- data collection
- data wrangling
- exploratory data analysis
- interactive visualization
- predictive modeling

The central question is:

Can the success of a Falcon 9 first-stage landing be predicted from mission
features such as launch site, payload mass, orbit, and booster version?

## Contents

The project includes the following components:

- Data collection from the SpaceX API
- Web scraping of Falcon 9 launch records
- Data cleaning and preparation with Pandas
- Exploratory data analysis using SQL and visualization libraries
- Interactive map visualization with Folium
- Dashboard development with Plotly Dash
- Classification models using scikit-learn

## Results

Several classification models were trained and compared, including:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- K-Nearest Neighbors

The best-performing model was a Decision Tree classifier. The analysis also
showed that factors such as flight number, payload mass, launch site, and
hardware-related features were relevant for predicting landing success.

## Limitations

This project was developed within a guided educational framework. The dataset
is relatively small, and some features, such as flight number, may reflect
technological progress over time rather than purely independent mission
properties.

The results should therefore be interpreted as a practical demonstration of
the data science workflow rather than as a production-level predictive system.

## Tools

- Python
- Pandas
- NumPy
- SQL / SQLite
- Matplotlib / Seaborn
- Folium
- Plotly Dash
- scikit-learn
- Jupyter Notebook

## Notes

This project serves as a practical demonstration of core data science skills:
collecting data, preparing it for analysis, exploring relationships,
visualizing results, and training basic machine learning models.
