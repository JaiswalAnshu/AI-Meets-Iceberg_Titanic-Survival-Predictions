# 🚢 Titanic - Machine Learning from Disaster
**Predicting Titanic Survivors using Machine Learning**

![Titanic_pic](https://github.com/user-attachments/assets/7e21ba16-54ac-408f-92ec-9c5679e325eb)

## 📌 Overview
This project focuses on using the Titanic passenger data (name, age, price of ticket, etc) to try to predict survival of Passangers in the Titanic ship .

The data has three files :<br>
(1) train.csv : This contains the Data for training the model .<br>
(2) test.csv : This contains the Data for testing the model . <br>
(3) submission.csv : This contains the Data we have got as a result of the model training . 

The train.csv has one extra column named "Survived" which can be used to determine whether each passenger survived or not:

- if it's a "1",in the column value the passenger survived.
- if it's a "0", the passenger died.

Using the patterns found in train.csv, the survival chances for passengers in test.csv were predicted . And this was done using Random Forest algorithm .

## 📂 Dataset
The dataset includes following features:

- survival	(0 = No, 1 = Yes)
- pclass	(Ticket class	1 = 1st, 2 = 2nd, 3 = 3rd)
- sex	
- Age	
- sibsp	   (# of siblings / spouses aboard the Titanic	)
- parch	   (# of parents / children aboard the Titanic)
- ticket	
- fare	
- cabin
- embarked	(Port of Embarkation	C = Cherbourg, Q = Queenstown, S = Southampton)
- Survival status (Target variable: Survived = 1, Not Survived = 0)


## 🛠️ Technologies Used
- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning Model)

## 📊 Steps Followed:

<br>1️⃣ Exploratory Data Analysis (EDA)
<br>- Checking missing values & data distribution
<br>- Visualizing survival rates with respect to different features .

<br>2️⃣ Feature Engineering
<br>- Handling missing values
<br>- Converting categorical variables using pd.get_dummies().

<br>3️⃣ Model Building
<br>- Used Random Forest Classifier for prediction.
<br>- Tuned n_estimators, max_depth, and random_state

<br>4️⃣ Evaluation & Submission
<br>- Predicted survival on test data
<br>- Generated CSV file  for submission

## 📌 Results
Achieved a decent accuracy score using Random Forest Classifier, demonstrating the effectiveness of ML models in classification problems!

## 📂 Project Structure
📂 AI-Meets-Iceberg_Titanic-Survival-Predictions  
│── 📊 Dataset/  
│── 📜 AI-Meets-Iceberg_Titanic-Survival-Predictions.ipynb  
│── 📜 README.md  
│── 📜 requirements.txt  

