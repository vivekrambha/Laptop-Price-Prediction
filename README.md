# Predicting Laptop Prices in India Using Machine Learning

## Overview
This repository contains the code and datasets used in the machine learning project aimed at predicting laptop prices in the Indian market. The project utilizes regression and decision tree models to estimate prices based on various laptop specifications.

## Abstract
Laptops are indispensable in our daily lives, serving a multitude of purposes. This project tackles the challenge of predicting laptop prices using supervised machine learning techniques. The study aims to assist consumers, manufacturers, and retailers by providing a model that estimates laptop prices based on specifications such as RAM, screen resolution, CPU, and other relevant features.

## Data
The dataset used for this project was sourced from Kaggle and includes a range of laptop specifications and their market prices. It consists of 1302 entries across 11 columns. Preprocessing steps were taken to ensure the data's quality and relevance for model training.

## Files
- `Data_Analytics_Project.ipynb`: Jupyter notebook with the full analysis, including data preprocessing, feature engineering, model training, and evaluation.
- `data/`: Folder containing the dataset used in the analysis.
- `figures/`: Visualizations generated from the analysis.
- `models/`: Trained machine learning models ready for prediction.

## Methodologies
The methodologies section of the project details the supervised learning techniques used, emphasizing regression analysis suitable for modeling continuous variables like price. Data preprocessing and feature engineering steps are outlined along with model selection and implementation strategies.

## Results
The linear regression model achieved an R² of 0.8539, while the random forest model had an R² of 0.7969. A detailed analysis of model performance is provided in the notebook.

## Analysis
Insights into the nuances of laptop pricing are discussed, including the significance of CPU brand and clock speed, as visualized in the scatter plots.

## Conclusion and Future Direction
The models demonstrate a significant ability to predict laptop prices, suggesting avenues for future enhancement, including integrating customer ratings and brand reputation into the predictive models.

## Limitations
The models may not capture some complex non-linear interactions between features. Further research will explore advanced feature selection techniques.

## How to Use
To run the analysis:
1. Ensure you have Jupyter Notebooks installed.
2. Clone this repository.
3. Navigate to the notebook directory and run `Data_Analytics_Project.ipynb`.

## References
References to the studies and sources of data are provided in the Jupyter notebook and should be consulted for a deeper understanding of the methodologies and analysis.

## Contributors
- Sai Vivek Rambha
