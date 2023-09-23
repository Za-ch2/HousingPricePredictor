# House Price Prediction Project

This project aims to predict house prices using regression models. It explores different regression algorithms and evaluates their performance on a dataset containing various features related to houses.

## Project Structure

The project is organized into milestones, each covering specific tasks and objectives.

### Milestone 3: Model Evaluation and Hyperparameter Tuning

In this milestone, we focused on evaluating and fine-tuning three different regression models: Linear Regression, Random Forest Regression, and Gradient Boosting Regression. We followed a structured approach:

1. **Data Preparation:**

   - Loaded the dataset from 'train.csv'.
   - Defined features (X) and the target variable (y).

2. **Model Selection:**

   - Initialized three regression models:
     - Linear Regression
     - Random Forest Regression
     - Gradient Boosting Regression

3. **Data Preprocessing:**

   - Handled missing values:
     - Imputed missing values in numerical features with the median.
     - Encoded categorical features using one-hot encoding.

   - Standardized numerical features using StandardScaler.

4. **Model Training:**

   - Trained the three selected models on the preprocessed training data.

5. **Model Evaluation (Linear Regression):**

   - Evaluated the Linear Regression model using RMSE (Root Mean Squared Error) and R-squared on the training and testing datasets.

6. **Model Evaluation (Random Forest Regression):**

   - Evaluated the Random Forest Regression model using RMSE and R-squared on the training and testing datasets.

7. **Model Evaluation (Gradient Boosting Regression):**

   - Evaluated the Gradient Boosting Regression model using RMSE and R-squared on the training and testing datasets.

8. **Hyperparameter Tuning (Gradient Boosting Regression):**

   - Performed hyperparameter tuning using GridSearchCV to find the best combination of hyperparameters for the Gradient Boosting Regression model.

9. **Final Model Evaluation:**

   - Evaluated the best-tuned Gradient Boosting Regression model on the testing dataset using RMSE and R-squared.

## Conclusion

The project showcases the evaluation and fine-tuning of regression models for house price prediction. Each model's performance was assessed, and the best-tuned model achieved the highest predictive accuracy.

