# diabetes-
# Data Description:
Pregnancies: Number of pregnancies the patient carried.
Glucose: Glucose level of the patient.
BloodPressure: Blood Pressure of the patient.
SkinThickness: How much skin thickness is there to patient.Skin thickness is primarily determined by collagen content and is increased in insulin-dependent diabetes mellitus (IDDM). We measured skin thickness in 66 IDDM patients aged 24-38 yr and investigated whether it correlated with long-term glycemic control and the presence of certain diabetic complications.
Insulin: Insulin level present in patient.
BMI: BMI of the patient.
Diabetes Pedigree Function: indicates the function which scores likelihood of diabetes based on family history.
Age: Age of the patient.
Outcome: 0 implies patient does not have diabetes. and 1 implies patient has diabetes.

# Analysis
Data has no missing values.
All features are arranged in currect format.
we find correlation matrix for each feature.
Then we use descriptive statistics to find the outliers.
So we perform boxplot for Insulin and BloodPressure and detect the outliers.
As a result we discard this values for better result.
We perform univariate analysis for each feature to observe its distribution. and it is found that all features follow normal distribution except Age, Insulin, Pregnancies, DiabetesPedigree function.
Then we seperate the target variable Outcome from the data to further analysis.
we then split the data into training and testing data by using train test split data.
we standardise the data to make the analysis correct.
We use RandomForestClassifier Algorithm to design the model for predicting whether the pateint will have diabetes or not?
