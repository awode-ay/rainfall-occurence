# Rainfall Occurrence Prediction Project
This project aims to predict rainfall occurrence using various climatic parameters.

## Data Overview
The dataset  contains the following columns:

MO: Month
DY: Day
T2M: Temperature at 2 meters above ground level
QV2M: Specific humidity at 2 meters above ground level
RH2M: Relative humidity at 2 meters above ground level
PS: Surface pressure
WS10M: Wind speed at 10 meters above ground level
PRECTCORR: Precipitation Correction
RF: Rainfall status (Rain/No-rain)

## Data Preprocessing
The data was loaded from climatedata3.csv file.
Replaced the string values of RF (rain/no-rain) with binary values (1/0).
Upsampled the minority class to address class imbalance.
Exploratory Data Analysis (EDA)
Basic statistical measures of the dataset were computed.
Value counts for Rain/No-rain status was visualized.
Correlation heatmap was plotted for the dataset.

## Model Evaluation
Multiple models were evaluated for performance:
- Logistic Regression
- Linear Discriminant Analysis
- K-Nearest Neighbors
- Decision Tree Classifier
- Gaussian Naive Bayes
- Support Vector Machine
- AdaBoost Classifier
- Gradient Boosting Classifier

Each model's accuracy was determined using cross-validation.
### Results
KNN had an accuracy of 92.1%
Decision Tree had an accuracy of 95.4%
Gradient Boosting had an accuracy of 91.7%
Additional evaluation metrics for these models are detailed in the code.
Additional Models
Artificial Neural Network: Implemented using MLPClassifier from sklearn.

### Random Forest Classifier: Used to determine feature importance.
