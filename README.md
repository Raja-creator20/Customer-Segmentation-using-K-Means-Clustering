**🛍️ Customer Segmentation using K-Means Clustering**

**📌 Overview**
This project performs Customer Segmentation using Unsupervised Machine Learning (Clustering) techniques. The goal is to group mall customers based on their spending behavior and income patterns, enabling targeted marketing strategies and data-driven business decisions.

We utilize the Mall Customers dataset (Kaggle) and apply K-Means Clustering, along with visual exploratory data analysis, scaling, and 3D interactive visualization to better understand customer patterns.

**🎯 Objectives**
Perform exploratory data analysis (EDA) on the customer dataset.

Apply feature scaling to standardize income and spending score.

Use K-Means clustering to segment customers.

Determine the optimal number of clusters (k) using the Elbow Method.

Visualize customer clusters using 2D and 3D scatter plots (Plotly).

Analyze the average spending and income per cluster for actionable insights.

(Bonus) Experiment with alternative clustering algorithms (e.g., DBSCAN).

**📂 Dataset**
The dataset used is the Mall Customers Dataset from Kaggle:

Columns:

CustomerID (Unique identifier)

Gender

Age

Annual Income (k$)

Spending Score (1-100)

We primarily focus on Annual Income and Spending Score, with Age included in the 3D visualization.



**🛠 Tools & Libraries**
Programming Language: Python

Libraries Used:

pandas – Data loading & preprocessing

numpy – Numerical operations

matplotlib & seaborn – Data visualization

scikit-learn – K-Means clustering, scaling

plotly – Interactive 3D visualization

**🔬 Methodology**
Data Preprocessing:

Load dataset and inspect structure.

Drop unnecessary columns (CustomerID).

Handle features relevant to clustering (Annual Income, Spending Score, Age).

Exploratory Data Analysis (EDA):

Visualize distributions (histograms/density plots) of Age, Income, Spending.

Identify spending behavior trends.

Feature Scaling:

Normalize/standardize features to bring them to the same scale.

**K-Means Clustering:**

Determine optimal k using the Elbow Method.

Fit K-Means model and assign cluster labels.

**Cluster Visualizatio**n:

Plot 2D scatter plots (Income vs. Spending Score).

Create 3D interactive Plotly visualization (Age vs. Income vs. Spending).

Cluster Analysis:

Analyze average spending and income per cluster.

Interpret clusters (e.g., High Income-High Spending (VIP) vs Low Income-Low Spending (Budget Customers)).

Bonus:

Experiment with DBSCAN clustering for density-based segmentation.

**📊 Results & Insights**
Segmented customers into 3 primary clusters:

Cluster 0: High income, high spending (VIP customers).

Cluster 1: Average income, moderate spending (Regular shoppers).

Cluster 2: Low income, low spending (Budget-conscious customers).

The segmentation helps businesses design personalized marketing campaigns, allocate budgets efficiently, and increase ROI.

**▶ How to Run**
Clone this repository or download the .ipynb file.

Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn plotly
Open the notebook in Jupyter Notebook or Google Colab.

Run all cells sequentially to reproduce results.

**🔥 Future Enhancements**
Integrate DBSCAN and Hierarchical Clustering for comparison.

Incorporate demographic features (e.g., Gender) for deeper segmentation.

Deploy model via Flask/Django API for real-time segmentation.

Use Principal Component Analysis (PCA) for dimensionality reduction in high-dimensional datasets.

**🧑‍💻 Author**
This project was developed by **RAJA SANA ULLAH** during my internship at Elevvo.Tec as part of my machine learning training.
As an aspiring Machine Learning Engineer, this project helped me strengthen my understanding of:

**Unsupervised learning (clustering techniques)**

**Data preprocessing and visualization**

**Real-world business insights through ML**

