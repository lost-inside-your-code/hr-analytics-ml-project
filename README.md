# hr-analytics-ml-project
Machine Learning project focused on predicting employee job satisfaction and resignation using HR data.

📌 Project Overview
This project is an applied Data Science and Machine Learning solution focused on analyzing HR data to support strategic decision-making in employee management.
The project consists of two key business tasks: 1. Predicting employee job satisfaction level (regression task) 2. Predicting employee resignation (attrition) (classification task)
Both tasks aim to help HR departments identify risk factors, improve employee retention strategies, and optimize workforce management.

🎯 Business Objectives
-	Identify key factors influencing employee satisfaction
-	Predict employees with a high risk of resignation
-	Provide actionable insights for HR to:
    -	reduce staff turnover
    -	improve motivation and engagement
    -	optimize career development and compensation strategies

🧠 Project Structure
The analysis is divided into two main parts:

Task 1: Employee Job Satisfaction Prediction
-	Type: Regression
-	Target: job_satisfaction_rate
-	Models tested:
    -	DecisionTreeRegressor
    -	LinearRegression
    -	RandomForestRegressor
-	Evaluation metric: SMAPE
✅ Best model: RandomForestRegressor
SMAPE on test set: 12.37 (target ≤ 15)

Task 2: Employee Attrition Prediction
-	Type: Binary Classification
-	Target: quit
-	Models tested:
    -	DecisionTreeClassifier
    -	LogisticRegression
    -	RandomForestClassifier
-	Evaluation metric: ROC-AUC
✅ Best model: RandomForestClassifier
ROC-AUC on test set: 0.9261 (target ≥ 0.9)
A predicted job satisfaction score was used as an additional feature to improve attrition prediction performance.

🔍 Key Findings
-	Employees with low job satisfaction, low salary and junior positions are significantly more likely to resign
-	The Sales department shows the highest turnover risk
-	Supervisor evaluation strongly correlates with both satisfaction and resignation
-	Job satisfaction is a critical predictor of attrition

💼 Business Impact
This project provides a data-driven foundation for HR strategy development:
-	Enables early identification of employees at risk of leaving
-	Supports targeted retention initiatives
-	Helps optimize employee development programs
-	Improves workforce stability and reduces hiring costs
By integrating predictive models into HR decision-making processes, companies can proactively address dissatisfaction factors and strengthen employee engagement.

🛠 Technologies Used
-	Python
-	Pandas, NumPy
-	Scikit-learn
-	Matplotlib, Seaborn
-	Phik
-	Jupyter Notebook
Methods: - Data preprocessing pipelines - Feature engineering - Cross-validation - Hyperparameter tuning (RandomizedSearchCV) - Model evaluation

📁 Repository Structure
hr-analytics/
├── hr_analytics.ipynb
└── README.md

🚀 How to Run
1.	Clone the repository
2.	Install required libraries
3.	Open hr_analytics.ipynb with Jupyter Notebook
4.	Run all cells in order

👩‍💻 Author
Anastasia Samsonova
Data Analyst / Aspiring Data Scientist
Berlin, Germany

If you have any questions or suggestions, feel free to reach out!
