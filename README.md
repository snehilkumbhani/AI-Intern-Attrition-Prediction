Employee Attrition Prediction
📌 Project Overview
This project aims to build an AI-powered system that predicts whether an employee is likely to leave the company (attrition) using the IBM HR Analytics Employee Attrition & Performance dataset. The system covers data preprocessing, model training, evaluation, and insights through visualizations.

📂 Dataset
Source: IBM HR Analytics Employee Attrition Dataset – Kaggle

Contains employee demographic, job role, and performance data.

Target variable: Attrition (Yes/No).

⚙️ Steps Performed
1. Data Understanding & Preprocessing
Loaded and explored the dataset.

Checked for missing values and handled them.

Encoded categorical features using Label Encoding / One-Hot Encoding.

Detected and addressed outliers where necessary.

Scaled numerical features using StandardScaler / MinMaxScaler.

Performed exploratory data analysis (EDA) with meaningful visualizations (Attrition by age, job role, and salary distribution).

2. Model Building
Chose classification algorithms: Logistic Regression and Random Forest.

Performed train-test split (e.g., 80/20 ratio).

Conducted basic hyperparameter tuning for improved performance.

Evaluated models using:

Accuracy

Precision

Recall

F1 Score

Confusion Matrix visualization

ROC-AUC curve

3. Results
Best performing model: Random Forest Classifier (highest F1 score and balanced precision-recall).

Key features influencing attrition: Job Role, Monthly Income, Overtime, Age, Job Satisfaction.

4. Research Brief (AI Trend)
Topic: Agentic AI (Autonomous AI Agents)

What is it? AI systems that can plan, decide, and act autonomously to achieve specific goals.

Why it matters? Enhances efficiency, reduces human intervention, and enables scalable automation.

Use case: AI agents for automated customer support that resolve queries end-to-end.

Challenges: Reliability, ethical concerns, and alignment with human values.

📊 Visualizations Included
Attrition rate by Age group

Attrition by Job Role

Correlation heatmap of numerical features

Confusion matrix for model evaluation

📁 Project Structure
java
Copy
Edit
AI-Intern-Attrition-Prediction
├── README.md                 <- Brief about the solution (this file)
├── data/                     <- Dataset or dataset link
├── notebooks/                <- Jupyter notebook(s)
├── models/                   <- Trained model files (optional)
├── report/                   <- PDF/Markdown report + Research Brief
🛠️ Technologies Used
Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Run all cells to see preprocessing, model training, and evaluation.