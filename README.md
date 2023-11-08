---

# SpaceX Falcon 9 First Stage Landing Prediction

Predicting the landing outcomes of SpaceX Falcon 9 first stage rocket boosters.

## Table of Contents

- [About](#about)
- [Dataset](#dataset)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Data Collection](#tata-collection)
- [Data Wrangling](#data-wrangling)
- [Data Visulization](#data-visulization)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [EDA with SQL](#eda-with-sql)
- [Machine Learning](#machine-learning)
- [Evaluation](#evaluation)
- [Acknowledgments](#acknowledgments)

## About

This project aim to predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## Dataset

The dataset used for this project contains information about SpaceX Falcon 9 rocket launches, including details about the launch site, landing outcomes, payload, and more. The dataset is available in dataset_part_1.csv, dataset_part2.csv, and feature_one_hot.csv

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have the following software/tools installed:

- Python (3.7 or higher)
- Jupyter Notebook/Visual Studio(IDE)
- pandas(for data analysis)
- NumPy(for data analysis)
- Matplotlib, Folium, and Seaborn(Data Visulization)
- Requests(to make HTTP requests)
- sqlite3(to connect to database)
- scikit-learn (for machine learning)

### Installation

1. Clone the repository:
2. Install the required Python packages:
   use !pip or !mamba python package managers to install the required libraries .

## Data Collection

Collect data using SpaceX API and Web-Scraping from Wikipedea.

## Data Wrangling

In this part of the project, we performed the following tasks:

1. Performed data wrangling(clean/format the data)
2. Made data ready for model training(performed one-hot-encoding)

## Data Visulization

Visulize insights using matplotlib and folium.

## Exploratory Data Analysis

Explore the dataset using Jupyter Notebook. Run the provided Jupyter Notebook to perform data analysis, visualize data, and gain insights from the SpaceX Falcon 9 launch data.

## Machine Learning

Build and train machine learning models to predict landing outcomes. The project uses various algorithms, including Logistic Regression, Support Vector Machine, Decision Trees, and k-Nearest Neighbors. Hyperparameter tuning is also performed to optimize model performance.

## Evaluation

Evaluate the performance of machine learning models using appropriate metrics. Compare and select the best model for predicting SpaceX Falcon 9 first stage landing outcomes.

## Contributing

If you'd like to contribute to this project, follow these steps:

1. Fork the project.
2. Create a new branch (`git checkout -b feature`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature`)
5. Open a pull request

## Acknowledgments

- Special thanks to SpaceX for making their launch data available.
- Thanks to the open-source community for providing tools and libraries used in this project.
