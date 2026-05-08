🚗 Car Evaluation using Data Mining
📌 Project Overview
This project applies data mining techniques to evaluate car acceptability based on multiple attributes such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and safety rating. The goal is to classify cars into categories like unacceptable, acceptable, good, and very good using machine learning models.

📊 Dataset
Source: UCI Machine Learning Repository – Car Evaluation Dataset

Attributes:

Buying price (low, med, high, vhigh)

Maintenance cost (low, med, high, vhigh)

Number of doors (2, 3, 4, 5more)

Passenger capacity (2, 4, more)

Luggage boot size (small, med, big)

Safety (low, med, high)

Target: Car acceptability (unacc, acc, good, vgood)

🔍 Methodology
Data Preprocessing:

Encoded categorical variables into numerical values.

Checked for missing values and ensured dataset consistency.

Exploratory Data Analysis (EDA):

Frequency distribution of attributes.

Correlation analysis between features and target.

Modeling:

Decision Trees

Random Forest

Naïve Bayes

K‑Nearest Neighbors (KNN)

Evaluation Metrics:

Accuracy

Precision, Recall, F1‑Score

Confusion Matrix

📈 Results
Random Forest achieved the highest accuracy due to its ability to handle categorical features and reduce overfitting.

Decision Tree provided interpretable rules for car evaluation.

Naïve Bayes performed well on categorical distributions but slightly lower accuracy.

💡 Insights
Safety and maintenance cost are the most influential attributes in determining car acceptability.

Cars with high safety and low maintenance cost are consistently rated as good or very good.

The dataset demonstrates how categorical attributes can be effectively mined for decision support.

🎯 Applications
Consumer Guidance: Helps buyers evaluate cars based on key attributes.

Automobile Industry: Assists manufacturers in understanding consumer priorities.

Educational Use: Demonstrates classification techniques in data mining courses.

🚀 How to Run
Clone the repository.

Install dependencies:

bash
pip install -r requirements.txt
Run the notebook:

bash
jupyter notebook Car_Evaluation.ipynb
