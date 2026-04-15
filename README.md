# DevelopersHub Corporation - Data Science & Analytics Internship

**Intern:** Kainat Murtaza  
**Duration:** March - April 2026  
**Tasks Completed:** 6 out of 10 (3 Phase 1 + 3 Phase 2)

---

## 📌 Quick Overview

This repository contains my completed tasks for the Data Science & Analytics Internship at DevelopersHub Corporation. I've completed 6 tasks across two phases, covering both foundational and advanced data science concepts.

### Phase 1: Foundational Tasks

| Task | Topic | Type | Status |
|------|-------|------|--------|
| Task 1 | Iris Dataset Analysis | Exploratory Data Analysis | ✅ Complete |
| Task 2 | Credit Risk Prediction | Binary Classification | ✅ Complete |
| Task 4 | Insurance Claim Prediction | Regression | ✅ Complete |

### Phase 2: Advanced Tasks

| Task | Topic | Type | Status |
|------|-------|------|--------|
| Task 1 | Term Deposit Subscription Prediction | Classification + XAI (SHAP) | ✅ Complete |
| Task 2 | Customer Segmentation | Unsupervised Learning (K-Means) | ✅ Complete |
| Task 5 | Interactive Business Dashboard | Streamlit / BI Dashboard | ✅ Complete |

---

## 📂 Phase 1: Foundational Tasks

### 🌸 Task 1: Iris Dataset Analysis

**Goal:** Understand patterns, visualize relationships, and spot which features separate different flower species.

**What I did:**
- Loaded the Iris dataset and checked its structure (150 flowers, 5 measurements per flower)
- Created scatter plots to see how sepal and petal dimensions relate to each other
- Built histograms to understand how each measurement is distributed across species
- Made box plots to check for unusual values (outliers)
- Generated a correlation heatmap to see which measurements move together

**Key finding:** Petal length and width are best friends (correlation of 0.96). Setosa flowers are the easy ones - their petals are much smaller than the other two species.

**Files generated:**
- `iris_analysis_visualizations.png` - All my charts in one place
- `iris_correlation_matrix.png` - Heatmap showing feature relationships

---

### 💳 Task 2: Credit Risk Prediction

**Goal:** Build a model that predicts whether a loan applicant is likely to default. Banks use this to decide who gets a loan.

**What I did:**
- Created a realistic loan dataset with 1,000 applications
- Handled missing values (real data is never perfect - about 5% of entries had gaps)
- Visualized how factors like income, education, and credit history affect approval
- Trained two models: Logistic Regression and Decision Tree
- Evaluated them using accuracy scores and confusion matrices

**Key finding:** Credit history is the king here. Applicants with good credit are 3x more likely to get approved. The best model hit about 75% accuracy.

**Files generated:**
- `credit_risk_analysis.png` - Visualizations of what factors matter
- `credit_risk_confusion_matrices.png` - How often each model gets it right vs wrong

---

### 🏥 Task 4: Insurance Claim Prediction

**Goal:** Predict how much someone will pay for medical insurance based on their age, BMI, smoking status, and other personal details.

**What I did:**
- Created synthetic customer data matching real-world patterns (1,338 customers)
- Explored which factors drive costs using scatter plots and box plots
- Trained 4 different regression models to see which works best
- Measured performance using MAE, RMSE, and R²
- Identified which features matter most for prediction

**Key finding:** Smoking is everything. Smokers pay about $15,000 more per year than non-smokers. The Random Forest model performed best, explaining 86% of cost variation.

**Files generated:**
- `insurance_analysis.png` - All my exploratory plots
- `insurance_correlation.png` - Which factors relate to higher costs
- `insurance_feature_importance.png` - What drives insurance prices most
- `insurance_model_comparison.png` - Which model performed best
- `insurance_predictions_vs_actual.png` - How close our predictions are to reality

---

## 🚀 Phase 2: Advanced Tasks

### 📞 Task 1: Term Deposit Subscription Prediction

**Goal:** Predict whether a bank customer will subscribe to a term deposit based on marketing campaign data. This helps banks target the right customers and reduce wasted calls.

**What I did:**
- Created a realistic bank marketing dataset with 4,521 customer records
- Encoded categorical features and scaled numerical features
- Trained two classification models: Logistic Regression and Random Forest
- Evaluated using F1-Score, ROC-AUC, and Confusion Matrices
- Used **SHAP (Explainable AI)** to explain individual predictions
- Identified top factors influencing subscription decisions

**Key finding:** 
- Random Forest performed best with F1-Score of 0.72 and ROC-AUC of 0.81
- Call duration is the strongest predictor - longer calls = more interest
- Previous campaign success and job type (management/retired/student) also matter significantly
- Best months to run campaigns: March, September, and December

**Files generated:**
- `task1_eda_visualizations.png` - Age, job, education, and call duration analysis
- `task1_confusion_matrices.png` - Model performance comparison
- `task1_roc_curves.png` - ROC curves showing model discrimination ability
- `task1_shap_summary.png` - SHAP feature importance (which factors matter most)
- `task1_feature_importance.png` - Top 15 features ranked by importance

**Business Impact:** The bank can now score customers before calling them, focusing marketing budget on high-probability leads and saving millions in wasted call center costs.

---

### 🛍️ Task 2: Customer Segmentation Using Unsupervised Learning

**Goal:** Cluster customers based on spending habits and propose tailored marketing strategies for each segment.

**What I did:**
- Created a mall customer dataset with 200 customers (age, gender, income, spending score)
- Applied K-Means clustering to find natural customer groups
- Used Elbow Method and Silhouette Score to determine optimal number of clusters (k=5)
- Visualized clusters using scatter plots, PCA, and t-SNE
- Developed specific marketing strategies for each customer segment

**Key finding:** 
- Identified 5 distinct customer segments:
  1. **💰 Platinum Spenders** - High income, high spending (20% of customers)
  2. **⭐ Gold Standard** - Medium income, regular spenders (20%)
  3. **🌱 Budget Conscious** - Low income, careful spenders (20%)
  4. **🏦 Smart Savers** - High income, low spending (20%)
  5. **🎯 Aspirational Shoppers** - Moderate income, loves to shop (20%)
- Silhouette Score of 0.45 confirms good cluster separation

**Files generated:**
- `task2_eda_visualizations.png` - Age, gender, income, and spending distributions
- `task2_optimal_k_analysis.png` - Elbow method and silhouette score graphs
- `task2_cluster_visualization.png` - Final customer segments with cluster centers
- `task2_pca_tsne_visualization.png` - Alternative views confirming cluster separation

**Business Impact:** The marketing team can now:
- Send luxury offers to Platinum Spenders
- Focus on value messaging for Budget Conscious customers
- Offer "Buy Now, Pay Later" options for Aspirational Shoppers
- Highlight quality and durability for Smart Savers

---

### 📊 Task 5: Interactive Business Dashboard

**Goal:** Build an interactive dashboard for analyzing sales, profit, and segment-wise performance.

**What I did:**
- Created a realistic sales dataset with 5,000 transactions (Global Superstore style)
- Built an interactive Streamlit dashboard with filters for Region, Category, Sub-Category, Segment, and Date Range
- Displayed key KPIs: Total Sales, Total Profit, Profit Margin, Avg Discount, Total Orders, Avg Order Value
- Created 9 visualizations including bar charts, pie charts, scatter plots, and trend lines
- Added business insights and actionable recommendations

**Key finding:**
- Technology category drives the highest sales and profit
- Corporate customers have the highest average order value
- Discounts over 20% significantly reduce profit margins
- North America and Europe are the best-performing regions

**Files generated:**
- `task5_dashboard.png` - Complete dashboard with 9 visualizations
- `task5_dashboard.py` - Streamlit app code (interactive version)

**Interactive Features:**
- Filter by Region, Category, Sub-Category, Customer Segment
- Date range selector for time-based analysis
- Drill-down capability to explore specific segments
- Real-time updates as filters change

**Business Impact:** Stakeholders can now explore data on their own without waiting for reports, making faster, data-driven decisions about inventory, marketing spend, and regional strategy.

---

## 🛠️ Tech Stack

Here's what I used to build all this:

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Main programming language |
| pandas | Data manipulation (think Excel on steroids) |
| numpy | Numbers and calculations |
| matplotlib | Basic plotting |
| seaborn | Fancy statistical visualizations |
| scikit-learn | Machine learning models (classification, clustering, regression) |
| SHAP | Explainable AI - understanding model predictions |
| Streamlit | Interactive dashboard web apps |
| Jupyter Notebook | Interactive development environment |

---

## 📁 Repository Structure
DevelopersHub-Internship/
│
├── Phase1_Foundational/
│ ├── Task1_Iris_Analysis/
│ │ ├── Task1_Iris_Dataset_Analysis.ipynb
│ │ ├── iris_analysis_visualizations.png
│ │ └── iris_correlation_matrix.png
│ │
│ ├── Task2_Credit_Risk/
│ │ ├── Task2_Credit_Risk_Prediction.ipynb
│ │ ├── credit_risk_analysis.png
│ │ └── credit_risk_confusion_matrices.png
│ │
│ └── Task4_Insurance_Claims/
│ ├── Task4_Insurance_Claim_Prediction.ipynb
│ ├── insurance_analysis.png
│ ├── insurance_correlation.png
│ ├── insurance_feature_importance.png
│ ├── insurance_model_comparison.png
│ └── insurance_predictions_vs_actual.png
│
└── Phase2_Advanced/
├── Task1_Term_Deposit/
│ ├── Task1_Term_Deposit_Prediction.ipynb
│ ├── task1_eda_visualizations.png
│ ├── task1_confusion_matrices.png
│ ├── task1_roc_curves.png
│ ├── task1_shap_summary.png
│ └── task1_feature_importance.png
│
├── Task2_Customer_Segmentation/
│ ├── Task2_Customer_Segmentation.ipynb
│ ├── task2_eda_visualizations.png
│ ├── task2_optimal_k_analysis.png
│ ├── task2_cluster_visualization.png
│ └── task2_pca_tsne_visualization.png
│
└── Task5_Dashboard/
├── task5_dashboard.py (Streamlit version)
├── task5_dashboard.png (Static dashboard)
└── README.md

---

## 📊 Key Achievements Summary

| Phase | Task | Best Model / Result | Key Metric |
|-------|------|---------------------|------------|
| 1 | Iris Analysis | Correlation Analysis | Petal correlation: 0.96 |
| 1 | Credit Risk | Logistic Regression | 75% accuracy |
| 1 | Insurance Claims | Random Forest | R² = 0.862 |
| 2 | Term Deposit | Random Forest | ROC-AUC = 0.81 |
| 2 | Customer Segmentation | K-Means (k=5) | Silhouette = 0.45 |
| 2 | Sales Dashboard | Streamlit | 9 interactive visualizations |

---

## 💡 What I Learned

**From Phase 1:**
- Always check your data structure first - know what you're working with
- Visualizations tell stories that numbers alone can't
- Simple models can perform as well as complex ones
- Different problems need different evaluation metrics

**From Phase 2:**
- Explainable AI (SHAP) helps build trust with stakeholders
- Customer segmentation turns data into actionable marketing strategies
- Interactive dashboards empower business users to explore data themselves
- Real-world data is messy - handling missing values is crucial

---

## 🚀 How to Run

### For Jupyter Notebooks (Phase 1 & 2 Tasks):
```bash
jupyter notebook
# Open the respective .ipynb file
# Run all cells