# Diabetes Prediction Model

This project aims to predict whether a patient should be tested for diabetes based on various health metrics. The model is trained using a dataset of patient information and evaluated for its accuracy and performance.

## Dataset

The dataset used for this project is `diabetes.csv`, which contains the following columns:

- `ID`: Patient ID
- `Pregnancies`: Number of pregnancies
- `PlasmaGlucose`: Plasma glucose concentration
- `DiastolicBloodPressure`: Diastolic blood pressure (mm Hg)
- `TricepsThickness`: Triceps skinfold thickness (mm)
- `SerumInsulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body mass index (weight in kg/(height in m)^2)
- `DiabetesPedigree`: Diabetes pedigree function
- `Age`: Age (years)
- `Diabetic`: Class variable (0 or 1)

## Notebook

The main analysis and model training are performed in the Jupyter Notebook [classification.ipynb](classification.ipynb). The notebook includes the following steps:

1. **Data Loading and Exploration**:

   - Load the dataset and display the first few rows.
   - Separate features (`X`) and labels (`y`).

2. **Data Visualization**:

   - Box plots to compare feature distributions for each label value.

3. **Data Splitting**:

   - Split the data into training and testing sets (70%-30%).

4. **Model Training**:

   - Train a logistic regression model on the training set.

5. **Model Evaluation**:

   - Evaluate the model using the test data.
   - Calculate accuracy, precision, recall, and F1-score.
   - Generate a confusion matrix.
   - Plot the ROC curve and calculate the AUC.

6. **Prediction**:
   - Make predictions on new data points.
