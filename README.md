# The-Invisible-Threat-Air-Quality-Prediction-System
Air pollution is a major environmental and health concern worldwide. This project focuses on building a Machine Learning-based Air Quality Prediction System that analyzes pollution data and predicts air quality levels. The goal is to provide a simple, fast, and accurate way to understand air conditions using data-driven insights.
Features
Predicts air quality categories: Good, Moderate, Poor, Hazardous
Uses key environmental parameters like PM2.5, PM10, CO, NO₂
Implements multiple ML algorithms for comparison
Uses Random Forest as the final optimized model
Interactive and user-friendly interface built with Gradio
Real-time prediction based on user input
Machine Learning Workflow
Data Collection
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training (Random Forest, SVM, Logistic Regression)
Model Evaluation & Comparison
Final Prediction System
Tech Stack
Python
Pandas, NumPy
Scikit-learn
Matplotlib, Seaborn
Gradio
Model Details
Multiple supervised learning models were trained and evaluated
Random Forest achieved the best performance in terms of accuracy and reliability
Final model is integrated into a web-based interface
How to Run
Bash
# Clone the repository
git clone https://github.com/nayana508/air-quality-prediction.git

# Navigate to project folder
cd air-quality-prediction

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
Output
The system takes pollution values as input and displays the predicted air quality category instantly through an interactive interface.
Dataset
Dataset sourced from Kaggle:
https://www.kaggle.com/dataset/mujtabmatin/air-quality-and-pollution-assessment⁠�
Conclusion
This project demonstrates how machine learning can be effectively used to predict air quality and address real-world environmental challenges. It provides an accessible tool for understanding pollution levels and promoting awareness.
