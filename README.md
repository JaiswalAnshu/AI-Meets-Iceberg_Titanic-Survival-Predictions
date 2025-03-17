🚢 Titanic - Machine Learning from Disaster
Predicting Titanic Survivors using Machine Learning

📌 Overview
This project focuses on using the Titanic passenger data (name, age, price of ticket, etc) to try to predict survival of Passangers in the Titanic ship .

The data has three files :
(1) train.csv : This contains the Data for training the model .
(2) test.csv : This contains the Data for testing the model . 
(3) submission.csv : This contains the Data we have got as a result of the model training . 

The train.csv has one extra column named "Survived" which can be used to determine whether each passenger survived or not:

- if it's a "1",in the column value the passenger survived.
- if it's a "0", the passenger died.

Using the patterns found in train.csv, the survival chances for passengers in test.csv were predicted . And this was done using Random Forest algorithm .

📂 Dataset
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


🛠️ Technologies Used
- Python
- Pandas, NumPy (Data Manipulation)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-Learn (Machine Learning Model)

📊 Steps Followed:

1️⃣ Exploratory Data Analysis (EDA)
- Checking missing values & data distribution
- Visualizing survival rates with respect to different features .

2️⃣ Feature Engineering
- Handling missing values
- Converting categorical variables using pd.get_dummies().

3️⃣ Model Building
- Used Random Forest Classifier for prediction.
- Tuned n_estimators, max_depth, and random_state

4️⃣ Evaluation & Submission
- Predicted survival on test data
- Generated CSV file  for submission

📌 Results
Achieved a decent accuracy score using Random Forest Classifier, demonstrating the effectiveness of ML models in classification problems!

