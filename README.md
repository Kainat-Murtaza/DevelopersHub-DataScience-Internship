# DevelopersHub Corporation - Data Science & Analytics Internship

Intern:Kainat MUrtaza  
Duration: March 2026  
Tasks Completed: 3 out of 5  

---

##  Quick Overview

This repository contains my completed tasks for the Data Science & Analytics Internship at DevelopersHub Corporation. I've completed 3 tasks that cover the core areas of data science: exploratory analysis, classification, and regression.

| Task | Topic | Type | Status |
|------|-------|------|--------|
| Task 1 | Iris Dataset Analysis | Exploratory Data Analysis |  Complete |
| Task 2 | Credit Risk Prediction | Binary Classification |  Complete |
| Task 4 | Insurance Claim Prediction | Regression | Complete |

---

## Details

##  Task 1: Iris Dataset Analysis

Goal: understand patterns, visualize relationships, and spot which features separate different flower species.

What I did:
- Loaded the Iris dataset and checked its structure (150 flowers, 5 measurements per flower)
- Created scatter plots to see how sepal and petal dimensions relate to each other
- Built histograms to understand how each measurement is distributed across species
- Made box plots to check for unusual values (outliers)
- Generated a correlation heatmap to see which measurements move together

Key finding: Petal length and width are best friends (correlation of 0.96). Setosa flowers are the easy ones - their petals are much smaller than the other two species.

Files generated:
- `iris_analysis_visualizations.png` - All my charts in one place
- `iris_correlation_matrix.png` - Heatmap showing feature relationships

---

##  Task 2: Credit Risk Prediction

Goal: Build a model that predicts whether a loan applicant is likely to default. Banks use this to decide who gets a loan.

What I did:
- Created a realistic loan dataset with 1,000 applications (since the Kaggle dataset requires download)
- Handled missing values (real data is never perfect - about 5% of entries had gaps)
- Visualized how factors like income, education, and credit history affect approval
- Trained two models: Logistic Regression and Decision Tree
- Evaluated them using accuracy scores and confusion matrices

Key finding: Credit history is the king here. Applicants with good credit are 3x more likely to get approved. The best model hit about 75% accuracy - not perfect, but useful for automating most decisions.

Files generated:
- `credit_risk_analysis.png` - Visualizations of what factors matter
- `credit_risk_confusion_matrices.png` - How often each model gets it right vs wrong

---

##  Task 4: Insurance Claim Prediction

Goal: Predict how much someone will pay for medical insurance based on their age, BMI, smoking status, and other personal details.

What I did:
- Created synthetic customer data matching real-world patterns (1,338 customers)
- Explored which factors drive costs using scatter plots and box plots
- Trained 4 different regression models to see which works best
- Measured performance using MAE (average error), RMSE (penalizes big errors), and R² (how much variation we explain)
- Identified which features matter most for prediction

Key finding: Smoking is everything. Smokers pay about $15,000 more per year than non-smokers. Age and BMI are next in line. The Random Forest model performed best, explaining 86% of cost variation.

Files generated:
- `insurance_analysis.png` - All my exploratory plots
- `insurance_correlation.png` - Which factors relate to higher costs
- `insurance_feature_importance.png` - What drives insurance prices most
- `insurance_model_comparison.png` - Which model performed best
- `insurance_predictions_vs_actual.png` - How close our predictions are to reality

---

##  Tech Stack

Here's what I used to build all this:

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Main programming language |
| pandas | Data manipulation (think Excel on steroids) |
| numpy | Numbers and calculations |
| matplotlib | Basic plotting |
| seaborn | Fancy statistical visualizations |
| scikit-learn | Machine learning models and evaluation |
| Jupyter Notebook | Interactive development environment |
