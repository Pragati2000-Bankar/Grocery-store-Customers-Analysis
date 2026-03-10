🛒 Grocery Store Customer Analysis
📌 Project Overview

This project analyzes grocery store customer purchasing behavior using data analysis and machine learning techniques. The goal is to identify different types of customers based on their purchasing patterns and build models that can predict customer segments.

Customer segmentation helps businesses improve marketing strategies, product recommendations, and inventory management.

🎯 Objectives

- Analyze grocery store customer purchasing behavior.
- Segment customers into different groups using K-Means Clustering.
- Build machine learning models to predict customer categories.
- Help grocery stores optimize inventory and customer experience.

❗ Problem Statement

Grocery stores collect large amounts of customer purchasing data but often struggle to extract useful insights.
By identifying customer segments and predicting purchasing behavior, businesses can:
- Improve product recommendations
- Optimize stock and supply chain management
- Personalize marketing strategies
- Increase customer satisfaction

This project builds:
- A clustering model to segment customers
- Classification models to predict customer segments

📊 Dataset Information

The dataset contains 440 customers with annual spending on different grocery categories.

- Feature                                   	Description
- Channel	                                    Customer purchase channel
- Region	                                    Customer region
- Fresh	                                      Annual spending on fresh products
- Milk	                                      Annual spending on milk
- Grocery	                                    Annual spending on grocery items
- Frozen	                                    Annual spending on frozen products
- Detergents_Paper	                          Annual spending on detergents and paper
- Delicatessen	                              Annual spending on delicatessen products

🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

🔍 Exploratory Data Analysis (EDA)

The dataset was analyzed using:
- Data inspection (head(), info(), describe())
- Correlation analysis
- Heatmap visualization
-Pairplot visualization
These techniques helped understand relationships between different product categories.

⚙️ Data Preprocessing
Before applying machine learning models:
- Features were scaled using StandardScaler
- Numerical values were normalized for better model performance

🤖 Customer Segmentation using K-Means

Customer segmentation was performed using K-Means Clustering.

The Elbow Method was used to determine the optimal number of clusters.

Final result:
3 customer segments identified

📈 Cluster Insights
- Cluster 0 – Medium Spenders
Customers with moderate spending across most categories.

- Cluster 1 – Fresh & Frozen Buyers
Customers who spend heavily on fresh and frozen products.

- Cluster 2 – Retail Store Buyers
Customers who spend more on grocery, milk, and detergents.

🧠 Machine Learning Models
Several classification algorithms were trained to predict customer clusters:
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gradient Boosting
- Support Vector Machine (SVM)

📊 Model Performance
- Model	                         Accuracy
- Decision Tree	                   92%
- Random Forest	                   92%
- KNN	                             95%
- Gradient Boosting	               92%
- SVM	                             96%

Best Performing Models
- Support Vector Machine
- K-Nearest Neighbors

💡 Key Insights
- Grocery and Detergent spending are highly correlated.
- Customers show distinct purchasing patterns.
- Machine learning models can accurately classify customer segments.

🚀 Business Impact
This project helps grocery businesses:
- Identify high-value customer segments
- Improve targeted marketing campaigns
- Optimize inventory management
- Increase customer retention

🔮 Future Improvements
- Deploy model using Streamlit or Flask
- Build an interactive Power BI or Tableau dashboard
- Use Deep Learning models
- Integrate real-time retail data
