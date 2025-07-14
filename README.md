# 🧠 Customer Segmentation Using Clustering (Python)

## 📌 Objective

Segment customers based on demographic and behavioral data using **K-Means clustering** to identify distinct customer groups and inform **targeted marketing strategies**.

> 📊 The project identifies high-value customers, budget-focused buyers, and more—enabling companies to optimize campaigns, offers, and service strategies.

---

## 🗃 Dataset Overview

- **Source**: [Kaggle - Synthetic Sales Data](https://www.kaggle.com/)  
- **File**: `New 1000 Sales Record.xlsx`
- **Records**: ~1,000 customers
- **Features**: 
  - `Customer ID`, `Gender`, `Age`
  - `Annual Income`, `Spending Score`, `Product Category`
  - Behavioral attributes like frequency and recency

> 🧼 Dataset was cleaned, scaled, and prepared for modeling in Python.

---

## ⚙️ Tools & Technologies

| Tool             | Usage                                 |
|------------------|----------------------------------------|
| Python (Jupyter) | Core development                      |
| Pandas, NumPy     | Data processing                       |
| Matplotlib, Seaborn | Data visualization                  |
| Scikit-learn     | K-Means, PCA, Silhouette score         |
| Excel            | Initial dataset exploration            |

---

## 📆 Project Timeline

### ✅ Week 1: Data Cleaning & EDA

- Imported `.xlsx` file into a Jupyter Notebook
- Cleaned missing/incorrect entries
- Scaled numerical features using `StandardScaler`
- Visualized data distributions using histograms & box plots

📊 **EDA Outputs**: Age vs. Spending, Gender split, Correlation heatmap  

---

### ✅ Week 2: Clustering Models

- Applied **K-Means Clustering**
- Used:
  - **Elbow Method** to determine optimal `k`
  - **Silhouette Score** to validate clustering performance
- Visualized clusters using:
  - **Scatter Plots**
  - **PCA** for dimensionality reduction

📌 Optimal Clusters Identified: **5**

---

### ✅ Week 3: Cluster Profiling

- Defined characteristics of each cluster:
  - Age group
  - Income level
  - Spending habits
- Identified **5 unique customer personas**
- Created a **strategy mapping** for each group

---

### ✅ Week 4: Final Report & Presentation

- Finalized Jupyter Notebook with annotations
- Added labeled cluster plots
- Prepared a short presentation with:
  - Insights
  - Strategic recommendations
  - Charts & tables

---

## 🔍 Key Findings

| Cluster | Description                          | Insight                                 |
|---------|--------------------------------------|-----------------------------------------|
| 0       | High income, high spending           | Premium customers — Upsell opportunity  |
| 1       | Low income, moderate spending        | Budget shoppers — Discounts, bundles    |
| 2       | Loyal, moderate income, high spend   | Retain & reward loyalty                 |
| 3       | Young, low spend                     | New entrants — Educate & engage         |
| 4       | Older customers, low frequency       | Re-engage with personalized offers      |

---

## 💡 Marketing Recommendations

- 🎯 **Cluster 0**: Exclusive rewards, early product access
- 💸 **Cluster 1**: Affordable bundles, limited-time deals
- 💎 **Cluster 2**: Loyalty program with cashbacks
- 🧠 **Cluster 3**: Informational content & onboarding
- 📬 **Cluster 4**: Personalized email campaigns

---

## 📈 Output

### 🧾 Files Included:
- `Project.ipynb`: Full pipeline with explanations and results
- `New 1000 Sales Record.xlsx`: Original dataset
- `/images/`: https://1drv.ms/i/c/a9064c978fcc341e/EVYSuC5mrElKqR7ygCzutQ0BqyU8kLbe0OMbNJRWlwE9sQ?e=ARzItg
### 📷 Key Outputs:
- Elbow Curve
- Silhouette Plot
- Clustered Scatter Plot (with PCA)
- Cluster Profile Summary
