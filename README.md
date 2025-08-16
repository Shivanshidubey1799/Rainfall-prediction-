# Rainfall-prediction-
**Project Overview**

This project predicts whether it will rain on a given day using weather parameters like pressure, temperature, humidity, dewpoint, sunshine, and windspeed.
The dataset was cleaned, preprocessed, and balanced using downsampling before training a Random Forest Classifier with GridSearchCV hyperparameter tuning.

**Features**

✔️ Data cleaning & preprocessing (handling missing values, encoding categorical variables)
✔️ Exploratory Data Analysis (EDA) with histograms, boxplots, and correlation heatmaps
✔️ Addressed class imbalance using downsampling
✔️ Model training with Random Forest + GridSearchCV
✔️ Evaluation using cross-validation, confusion matrix, classification report
✔️ Model saving with Pickle for future predictions

**Workflow**

Data Preprocessing

Removed irrelevant features & handled missing values

Converted categorical rainfall labels (yes/no) to binary (1/0)

Balanced classes by downsampling

Exploratory Data Analysis (EDA)

Visualized distributions of weather parameters

Correlation heatmap to detect highly correlated features

Dropped redundant columns (maxtemp, temparature, mintemp)

Model Development

Trained Random Forest Classifier

Performed hyperparameter tuning with GridSearchCV

Validated using cross-validation

Model Evaluation

Achieved high accuracy on test set

Generated confusion matrix & classification report

Deployment Ready

Saved trained model as .pkl file

Supports predictions on new unseen data

 **Tech Stack**

Python 

Libraries:

pandas, numpy → Data preprocessing

matplotlib, seaborn → Data visualization

scikit-learn → Model training & evaluation

pickle → Model persistence

**Results**

Best Model: Random Forest Classifier (after GridSearchCV tuning)

Cross-validation Accuracy: ~ 95%

Test Accuracy: ~ 93%

Model successfully predicts Rainfall vs No Rainfall based on weather parameters.
