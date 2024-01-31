
# Loan Default Prediction Data Product





This repository hosts the code and documentation for a data product developed to identify loan defaults for a bank. The project utilized classification algorithms, including logistic regression, random forest, XGBoost, and SVM. The highest accuracy of 82 percent was achieved with the random forest model. The loan default process for the bank was optimized using insights derived from the analysis.


## Screenshots
![Imbalanced_dataset](https://github.com/vibhudixit123/ByteIQ-Analytics_internship_project/assets/104568465/436f7ff5-6c2c-459b-9f19-27742d940ad8)
![ROC_Score](https://github.com/vibhudixit123/ByteIQ-Analytics_internship_project/assets/104568465/9c1a7f0b-26d1-4a1c-882d-bbd8dd9e4dae)
![PowerBi Dashboard](https://github.com/vibhudixit123/ByteIQ-Analytics_internship_project/assets/104568465/bfcbae6c-ca62-4d4a-b0b7-cb09265725a9)

## DATA

The dataset used for training is stored in Raw_Data_Singapore_Credit_Dataset.csv, and the dataset for production prediction is Predict_Data_Singapore_Credit_Dataset.csv. These datasets contain relevant features necessary for loan default prediction.
## Classification Algorithms:

The classification algorithms used in this project are as follows:

Logistic Regression:

Logistic Regression is a linear model that predicts the probability of an instance belonging to a particular class.
It is particularly suitable for binary classification tasks, making it an excellent choice for predicting loan defaults or non-defaults.

Random Forest:

Random Forest is an ensemble learning method that builds a multitude of decision trees during training and outputs the mode of the classes as the prediction.
It excels in handling complex relationships in data and provides high accuracy, as observed in this project.

XGBoost:

XGBoost (Extreme Gradient Boosting) is a gradient boosting algorithm known for its efficiency and speed.
It sequentially builds decision trees and corrects errors made by the previous ones, making it powerful for classification tasks.

Support Vector Machine (SVM):


SVM is a powerful classification algorithm that finds the hyperplane that best separates instances of different classes.
It is effective in high-dimensional spaces and is capable of handling both linear and non-linear data.
## Optimization:

The loan default process for the bank was optimized based on insights obtained from the analysis and model predictions. The optimization process involved fine-tuning parameters, adjusting decision thresholds, and refining the overall decision-making workflow.
## Interactive Power BI Dashboard:

An interactive Power BI dashboard was created to present insightful data visualizations, allowing users to interact with and explore the findings from the model's analysis. The dashboard provides a user-friendly interface to understand the patterns and trends in the dataset.
## License

[MIT](https://choosealicense.com/licenses/mit/)

