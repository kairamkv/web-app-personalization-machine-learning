# Web Application Personalization with Machine Learning

## Overview

Web application personalization leverages machine learning to customize user experiences, tailoring content, recommendations, and interfaces based on individual preferences and behavior. This README.md provides an overview of the project code and its purpose.

## Project Code

The provided Python code in the file `DMGS_PRI_651045_2 Final.ipynb` focuses on exploring and analyzing web application data for personalization using machine learning techniques. Below is a summary of the code's main sections and tasks:

1. **Data Loading and Preprocessing**
   - Load and inspect the training and testing datasets.
   - Check for missing values in the datasets.

2. **Data Visualization**
   - Visualize data distribution using count plots.
   - Plot pie charts, scatter charts, and line charts to analyze dataset characteristics.

3. **Feature Engineering**
   - Create dummy variables.
   - Explore and analyze pairs of variables with scatterplots and histograms.

4. **Random Forest Models**
   - Build and train Random Forest Classifier models.
   - Split data into training and testing sets.
   - Visualize decision trees within the Random Forest.

5. **Model Evaluation**
   - Evaluate the performance of the Random Forest Classifier.
   - Display a confusion matrix and classification report.

6. **Label Encoding**
   - Label encode the 'eventType' column.
   - Split data into training and testing sets.

7. **Linear Regression Model**
   - Train a linear regression model to predict 'eventType'.
   - Calculate MAE, RMSE, and R-squared for model evaluation.

## Usage

To run the code and explore its functionality, you can follow these steps:

1. Clone or download this repository.

2. Open the Jupyter Notebook file `DMGS_PRI_651045_2 Final.ipynb` using a Jupyter Notebook environment.

3. Execute each code cell sequentially to perform data analysis and model training.

## Dependencies

Ensure you have the following Python packages installed:

- matplotlib
- seaborn
- pyarrow
- numpy
- pandas
- scikit-learn

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

By analyzing user behavior and preferences, web application personalization aims to enhance user engagement and satisfaction. Feel free to explore the code and adapt it to your specific use case for personalized web applications.
