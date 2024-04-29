# Predict Bike Sharing Demand with AutoGluon

## Introduction

This project utilizes AWS's open-source AutoML library, AutoGluon, to predict bike sharing demand using the Kaggle Bike Sharing demand dataset. The primary objective is to leverage AutoGluon's 'Tabular Prediction' to develop accurate AutoML-based baseline models, simplifying tasks such as data cleaning, feature engineering, hyperparameter optimization, and model selection.

## Overview

This project was undertaken as part of the assessment in the 'AWS x Udacity's Machine Learning Engineer Nanodegree Scholarship Program'.

### Problem Overview

Bicycle sharing programs, known as bike-sharing systems, offer a convenient method for renting bicycles through a network of kiosk locations in urban areas. These systems record travel duration, departure and arrival locations, and time elapsed, providing valuable insights into city mobility patterns. The Kaggle Bike Sharing Demand Competition challenges participants to predict bike rental demand in Washington D.C. based on historical usage patterns and weather data.

### Dataset

The project utilizes the Bike Sharing Demand Competition dataset, available [here](Bike-Sharing-Demand-Kaggle-Competition-Dataset-Link).

### Approach

1. **Data Analysis:** The dataset was analyzed to identify features and characteristics.
2. **Model Training:** AutoGluon's Tabular Prediction was used to train a baseline model with default settings.
3. **Exploratory Data Analysis (EDA):** In-depth analysis of existing features to improve model performance.
4. **Feature Engineering:** Incorporation of feature engineering techniques to enhance model performance.
5. **Model Iterations:** Multiple model iterations were performed to further improve performance, with hyperparameters fine-tuned using the feature-engineered dataset.

## Getting Started

### Resources

1. Clone the [template repository](git@github.com:udacity/nd009t-c1-intro-to-ml-project-starter.git) into AWS SageMaker Studio or local development environment.

### Dependencies

- Python 3.7
- pydantic 1.10.3
- MXNet 1.8
- Pandas >= 1.2.4
- AutoGluon 0.2.0

### Installation

- For Sagemaker Studio, follow provided instructions.
- For local development, set up a Jupyter Lab instance. Install Jupyter Lab using `pip install jupyterlab` or use Docker containers containing Jupyter Lab.

## Project Files

1. **project_notebook-bike_sharing_demand.ipynb:** Jupyter notebook with code.
2. **project_notebook-bike_sharing_demand.html:** HTML export of the Jupyter notebook.
3. **project_report.md:** Markdown report detailing model iterations and improvements.

## Acknowledgements

This project utilizes data from the Kaggle Bike Sharing Demand Competition provided by Hadi Fanaee Tork using data from Capital Bikeshare. Special thanks to Kaggle, Hadi Fanaee Tork et al., and the University of California, Irvine (UCI) machine learning repository for hosting the dataset.

If you use this dataset in your work, please cite:

Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge," Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg.

---

Feel free to adjust this template further to fit your specific repository's needs!
