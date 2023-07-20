# Heart Disease Prediction

The "Heart Disease Prediction" project focuses on predicting the presence of exercise-induced angina (exang) using a logistic regression model with one-hot encoding for categorical variables. The dataset "heart_disease_data.csv" contains various features related to heart health.

## Project Overview

1. **Data Loading**: The project loads the heart disease data from the "heart_disease_data.csv" file into a pandas DataFrame.

2. **Data Preprocessing**: The dataset is inspected for any missing values or data issues.

3. **Data Exploration**: Descriptive statistics and correlation analysis are performed to understand the data and identify potential patterns.

4. **Model Building**: A logistic regression model is built using one-hot encoding to handle categorical variables.

5. **Model Evaluation**: The accuracy score of the logistic regression model is computed on the test data.

6. **Feature Importance**: The odds ratios of the features are calculated to identify the most important predictors of exercise-induced angina.

7. **Confusion Matrix**: Confusion matrices are generated using both the default threshold (0.5) and an adjusted threshold (0.7) to visualize the model's performance.

## Dependencies

This project requires the following Python libraries:

- numpy
- pandas
- matplotlib.pyplot
- seaborn
- sklearn.model_selection.train_test_split
- sklearn.pipeline.make_pipeline
- sklearn.linear_model.LogisticRegression
- sklearn.metrics.ConfusionMatrixDisplay
- sklearn.metrics.confusion_matrix
- category_encoders.OneHotEncoder

You can install these dependencies using `pip`, the Python package manager, by running the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn category_encoders
```

## Usage

1. Clone this repository to your local machine.
2. Place the "heart_disease_data.csv" file in the same directory as the code files.
3. Run the provided Python script to execute the heart disease prediction model.
4. The script will display the accuracy score of the logistic regression model and generate confusion matrices with default and adjusted thresholds.

## Conclusion

The "Heart Disease Prediction" project showcases the application of logistic regression for predicting exercise-induced angina. By analyzing various heart health-related features, the model can provide valuable insights into the likelihood of exercise-induced angina in patients. The project's results and feature importance analysis contribute to a better understanding of factors influencing the presence of exercise-induced angina.

