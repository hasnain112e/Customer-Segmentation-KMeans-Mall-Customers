# Customer-Segmentation-KMeans-Mall-Customers
An unsupervised machine learning project to segment customers based on their annual income and spending score using the K-Means clustering algorithm. The project uses the Mall Customers dataset from Kaggle and includes steps for data cleaning, feature scaling, determining the optimal number of clusters using the Elbow Method, and visualizing 
# Customer Segmentation - K-Means Clustering (Mall Customers Dataset)

## 📌 Project Overview
This project applies **K-Means clustering** to the [Mall Customers dataset](https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial) to identify distinct customer segments based on **annual income** and **spending score**. The results can be used for targeted marketing and personalized offers.

## 📊 Dataset
- **Source:** Kaggle - Mall Customers Dataset
- **Rows:** 200 customers
- **Features:**
  - `CustomerID` – Unique customer identifier (dropped in preprocessing)
  - `Gender` – Male/Female (encoded as numeric)
  - `Age` – Customer age
  - `Annual Income (k$)` – Annual income in thousands of dollars
  - `Spending Score (1-100)` – Spending score assigned by the mall

## 🚀 Steps Performed
1. **Data Loading** – Imported CSV dataset from Kaggle
2. **Data Cleaning** – Dropped unnecessary `CustomerID` column, encoded `Gender`
3. **Feature Selection** – Selected `Annual Income (k$)` and `Spending Score (1-100)` for clustering
4. **Feature Scaling** – Standardized features for better clustering results
5. **Elbow Method** – Determined optimal number of clusters (`k`)
6. **K-Means Clustering** – Applied clustering and assigned segment labels
7. **Visualization** – Created scatter plot of clusters

## 🛠 Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## 📈 Output
- **Elbow Method plot** showing optimal cluster number
- **Scatter plot** visualizing customer segments
- **Clustered dataset** with `Cluster` column

## 🔧 How to Run
```bash
# Clone the repository
git clone https://github.com/yourusername/Customer-Segmentation-KMeans-Mall-Customers.git

# Install dependencies
pip install pandas matplotlib seaborn scikit-learn

# Run the script or Jupyter Notebook
python kmeans_customer_segmentation.py
