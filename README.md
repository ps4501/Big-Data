# Big-Data


## Table of Contents
1. [Introduction](#introduction)
2. [Time Series Forecasting](#time-series-forecasting)
    - [Overview](#overview)
    - [Installation](#installation)
    - [Usage](#usage)
3. [Recommendation System](#recommendation-system)
    - [Overview](#overview-1)
    - [Usage](#usage-1)
4. [Repository Structure](#repository-structure)
5. [Contributing](#contributing)


## Introduction
This repository contains two main projects related to Data Science:
1. **Time Series Forecasting**: A project focusing on analyzing temporal data to predict future values based on historical trends.
2. **Recommendation System**: A hybrid approach combining collaborative filtering and frequent pattern mining to generate personalized recommendations.

## Time Series Forecasting

### Overview
The Time Series Forecasting project focuses on analyzing temporal data to predict future values based on historical trends. The implementation leverages Python libraries such as pandas, numpy, and statsmodels to preprocess data, build models, and generate forecasts.

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ps4501/Big-Data.git
    cd Big-Data
    ```

### Usage
1. Open the Jupyter notebook `Time_series_forecasting.ipynb` to explore the code and execute the cells.
2. Follow the instructions within the notebook to preprocess the data, train the models, and evaluate their performance.

## Recommendation System

### Overview
The Recommendation System project is a hybrid approach combining collaborative filtering and frequent pattern mining to generate personalized recommendations. The system is tailored for a grocery store environment and addresses the cold start problem.

#### Key Components
- **Data Preprocessing**: Transforming transactional data into a suitable format, organizing it in a customer-based matrix.
- **Frequent Pattern Mining**: Using the FP-Growth algorithm to identify significant item associations.
- **Collaborative Filtering**: Applying techniques such as Data2Recommendation (D2R) and Pattern2Recommendation (P2R) to generate recommendations.
- **Cold Start Problem**: Implementing fallback mechanisms to handle new users with limited transaction history.
- **Evaluation**: Utilizing metrics like Root Mean Square Error (RMSE), Average Reciprocal Hit Rank (ARHR), Precision, Coverage, and Diversity to assess performance.

### Usage
1. Review the detailed methodology and results in the report `Recommendation_system.pdf`.
2. Implement the system based on the provided documentation and code snippets in the report.


## Contributions
1. Chahat Segan
2. Ujjwal Bhardwaj
