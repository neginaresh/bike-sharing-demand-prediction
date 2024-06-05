# Bike Sharing Demand Prediction

## Project Overview

BoomBikes, a US-based bike-sharing provider, has experienced a decline in revenue due to the COVID-19 pandemic. To prepare for a post-pandemic surge in demand, they need to understand the factors affecting bike demand and predict future demand accurately. This project aims to build a multiple linear regression model to predict the daily demand for shared bikes based on various factors.

## Data Description

The dataset used in this project contains daily bike demand data along with several independent variables that may influence the demand. These include meteorological data, seasonal information, and user behavior metrics.

## Key Steps in the Project

1. **Data Understanding and Preparation:**
    - Performed data quality checks and addressed missing values.
    - Converted categorical variables to dummy variables.
    - Derived new metrics and cleaned the data for analysis.

2. **Exploratory Data Analysis (EDA):**
    - Conducted EDA to understand the relationships between independent variables and the target variable (`cnt`).

3. **Model Building:**
    - Built a multiple linear regression model using the cleaned dataset.
    - Tuned model parameters and selected the best model based on key performance metrics.

4. **Model Evaluation:**
    - Evaluated the model using R-squared and other metrics.
    - Performed residual analysis and validated assumptions.

5. **Interpretation and Results:**
    - Identified significant variables contributing to bike demand.
    - Provided insights and recommendations based on the model.

## Results and Insights

- Significant variables: The top three features contributing significantly to bike demand were `temp`, `yr`, and `season`.
- Model performance: The model achieved a high R-squared value, indicating a good fit for the data.

## Repository Structure

- `day.csv`: The dataset used for analysis and model building.
- `bike_sharing_demand_prediction.ipynb`: Jupyter notebook with the complete code for data preparation, EDA, model building, and evaluation.
- `subjective_questions.pdf`: Answers to the subjective questions related to linear regression.
- `README.md`: This file, providing an overview of the project.

## How to Run the Code

1. Clone this repository.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`.
3. Open the Jupyter notebook and run the cells sequentially to see the analysis and results.

## Assumptions

- The data is representative of the entire bike-sharing demand in the US.
- Seasonal and weather-related variables are accurately recorded and impactful.

## Conclusion

This project provides a comprehensive analysis and predictive model for bike-sharing demand. It can help BoomBikes optimize their business strategy and prepare for increased demand post-pandemic.


Calculating the R-squared score on the test set for evaluating this model:

Train R-squared=0.844

Test R-squared=0.7795

Train Adj-R-squared=0.841

Test Adj-R-squared=0.832

That looks like an excellent model.


## Contact

For any queries or feedback, please contact Naresh Negi at naresh.negi@gmail.com.