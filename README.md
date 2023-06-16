# Project: Insurance Cost Prediction

## Data Collection and Analysis:

### Imported necessary dependencies: numpy, pandas, matplotlib, seaborn, sklearn.
Loaded the insurance dataset from a CSV file into a Pandas DataFrame.
Explored the dataset by displaying the first few rows, checking the shape, and obtaining information about the columns.
Checked for missing values (no missing values found).
Analyzed the categorical features: sex, smoker, and region.
Computed statistical measures of the dataset.
Visualized the distributions and counts of various features using seaborn and matplotlib.
Data Pre-processing:

### Encoded the categorical features: sex, smoker, and region, replacing their values with numerical representations.
Updated the DataFrame with the encoded values.
Splitting the Data:

Separated the features (X) and the target variable (Y) by dropping the 'charges' column.
Split the data into training and testing sets using the train_test_split function from sklearn.
Model Training:

Utilized the LinearRegression model from sklearn.linear_model.
Initialized the regressor and trained it using the training data.
Model Evaluation:

Predicted the insurance charges for both the training and testing data.
Calculated the R-squared value as a measure of the model's performance.
The R-squared values obtained for the training and testing sets were approximately 0.75, indicating a reasonably good fit.
Building a Predictive System:

Created an example input_data (age, sex, bmi, children, smoker, region) to predict insurance costs.
Converted the input data into a numpy array and reshaped it.
Utilized the trained model to predict the insurance cost based on the input data.
Results:

The linear regression model achieved an R-squared value of approximately 0.75 on both the training and testing data.
The model can be used to predict insurance costs based on the provided input data.
Potential Improvements:

Explore and experiment with other regression models to compare their performance.
Perform feature scaling or normalization to improve the model's accuracy.
Consider feature engineering techniques to derive additional useful features.
Evaluate the model using additional evaluation metrics, such as mean absolute error or mean squared error.
Gather more data to improve the model's generalization capabilities.
Optimize the model's hyperparameters using techniques like cross-validation or grid search.

# Medical_insurance_Cost_Prediciton![Medical insurance cost predicition 1](https://github.com/sanjeevrana90/Medical_insurance_Cost_Prediciton/assets/122264554/86a06256-7b53-474a-8b52-4e8ba8d147f6)
![Medical insurance cost predicition 2](https://github.com/sanjeevrana90/Medical_insurance_Cost_Prediciton/assets/122264554/9702b7dc-861f-4a93-8349-3484a01620c5)
