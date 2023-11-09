# SpaceX Falcon 9 First Stage Landing Prediction

Predicting the landing outcomes of SpaceX Falcon 9 first stage rocket boosters.

## Table of Contents

- [About](#about)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Collection](#data-collection)
- [Data Wrangling](#data-wrangling)
- [Data Visualization](#data-visualization)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [EDA with SQL](#eda-with-sql)
- [Machine Learning](#machine-learning)
- [Evaluation](#evaluation)
- [Project Structure](#project-structure)
- [Acknowledgments](#acknowledgments)

## About

This project aims to predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Dataset

The dataset used for this project contains information about SpaceX Falcon 9 rocket launches, including details about the launch site, landing outcomes, payload, and more. The dataset is available in dataset_part_1.csv, dataset_part2.csv, and feature_one_hot.csv.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have the following software/tools installed:

- Python (3.7 or higher)
- Jupyter Notebook/Visual Studio (IDE)
- pandas (for data analysis)
- NumPy (for data analysis)
- Matplotlib, Folium, and Seaborn (Data Visualization)
- Requests (to make HTTP requests)
- sqlite3 (to connect to the database)
- scikit-learn (for machine learning)

### Installation

1. Clone the repository.
2. Install the required Python packages:
   Use `!pip` or `!mamba` Python package managers to install the required libraries.

## Data Collection

Collect data using SpaceX API and Web-Scraping from Wikipedia.

## Data Wrangling

In this part of the project, we performed the following tasks:

1. Performed data wrangling (cleaned/format the data).
2. Made data ready for model training (performed one-hot-encoding).

## Data Visualization

Visualize insights using Matplotlib and Folium.

## Exploratory Data Analysis

Explore the dataset using Jupyter Notebook. Run the provided Jupyter Notebook to perform data analysis, visualize data, and gain insights from the SpaceX Falcon 9 launch data.

## Machine Learning

Build and train machine learning models to predict landing outcomes. The project uses various algorithms, including Logistic Regression, Support Vector Machine, Decision Trees, and k-Nearest Neighbors. Hyperparameter tuning is also performed to optimize model performance.

## Evaluation

Evaluate the performance of machine learning models using appropriate metrics. Compare and select the best model for predicting SpaceX Falcon 9 first stage landing outcomes.

## Project Structure

The project structure is organized as follows:

- README.md: The main project documentation.
- jupyter-labs-spacex-data-collection-api.ipynb: The Jupyter Notebook containing the project code for data collection using spaceX api.
- labs-jupyter-spacex-Data wrangling.ipynb: The Jupyter Notebook containing the project code for data cleaning.
- jupyter-labs-eda-dataviz.ipynb: The Jupyter Notebook containing the project code for EDA and data visulizations.
- jupyter-labs-eda-sql-coursera_sqllite.ipynb: The Jupyter Notebook containing the project code for EDA with SQL and data visulizations.
- SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb:The Jupyter Notebook containing the project code for machine learning model and visulizations.
- dataset_part_1.csv: The first part of the dataset.
- dataset_part_2.csv: The second part of the dataset.
- features_one_hot.csv: The dataset with one-hot encoding applied.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the project.
2. Create a new branch (`git checkout -b feature`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature`).
5. Open a pull request.

## Acknowledgments

- Special thanks to SpaceX for making their launch data available.
- Thanks to the open-source community for providing tools and libraries used in this project.
