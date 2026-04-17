# Student_Performance_Prediction
📌 Overview

This project predicts whether a student will Pass or Fail using Machine Learning algorithms based on key academic factors.

🚀 Features
Predicts student performance (Pass/Fail)
Uses multiple ML models:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
Automatically selects the best model
Includes EDA visualizations
Takes user input for real-time prediction

📊 Dataset
The dataset contains the following columns:
Student_ID
Study_Hours
Attendance
Previous_Marks
Assignments
Internal_Marks
Final_Result

⚙️ Technologies Used
Python
Pandas
Scikit-learn
Matplotlib
Seaborn

📈 Exploratory Data Analysis
Study Hours vs Previous Marks
Attendance vs Result

🧠 Model Training
Uses only key features:
Study_Hours
Attendance
Previous_Marks
Data preprocessing:
Missing value handling
Feature scaling
Train-test split: 80% / 20%

🏆 Results
Best Model: Logistic Regression
Accuracy: ~99%

▶️ How to Run
Install dependencies:
pip install pandas scikit-learn matplotlib seaborn
Run the script:
python your_file_name.py
Enter student details when prompted.

📌 Output
Displays model accuracy
Predicts:
PASS ✅ or FAIL ❌
Pass Probability

📁 Output Files
eda_analysis.png (EDA plots)
📌 Future Improvements

Web interface using Flask
More features for better prediction
Deployment on cloud
