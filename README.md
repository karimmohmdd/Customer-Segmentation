# 🛒 Customer Segmentation using Machine Learning

## 📌 Overview
This project applies Unsupervised Machine Learning techniques to segment mall customers based on their annual income and spending habits. The goal is to identify distinct customer groups to help tailor marketing strategies and improve business decisions.

## 📊 Dataset
The dataset used in this project contains information about mall customers, including:
- **CustomerID:** Unique ID assigned to the customer.
- **Gender:** Gender of the customer.
- **Age:** Age of the customer.
- **Annual Income (k$):** Annual income of the customer.
- **Spending Score (1-100):** Score assigned by the mall based on customer behavior and spending nature.

## 🛠️ Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn

## 🚀 Project Pipeline
1. **Data Preprocessing:** Handling missing values, scaling features using `StandardScaler`.
2. **Exploratory Data Analysis (EDA):** Understanding data distributions and relationships.
3. **Clustering Models:** - Applied **K-Means Clustering** and used the Elbow Method to find the optimal number of clusters.
   - Applied **DBSCAN** to identify clusters based on density and detect outliers.
4. **Evaluation & Visualization:** Visualizing the clusters in 2D plots for actionable insights.

## 📈 Results & Insights
Based on the clustering algorithms, we identified **5 main customer segments**:
- **VIP Customers:** High Income, High Spending.
- **Careful Customers:** High Income, Low Spending.
- **Average Customers:** Medium Income, Medium Spending.
- **Spendthrifts:** Low Income, High Spending.
- **Sensible Customers:** Low Income, Low Spending.

