📊 Customer Segmentation using K-Means

This project uses unsupervised machine learning (K-Means clustering) to segment customers based on their purchasing behavior. By analyzing frequency, quantity, and spending, businesses can better understand customer groups and design targeted marketing strategies.

Dataset:-
Dataset Name: Online Retail
Format: Excel (OnlineRetail.xlsx)
Features: Invoice, StockCode, Description, Quantity, Price, Customer ID, Country

After preprocessing, customer-level features were created:
Frequency → number of purchases
Quantity → total items bought
TotalAmount → total spending

Steps in the Project:-

1.Data Preprocessing
a.Handled missing values
b.Removed duplicates and invalid entries
c.Created TotalAmount = Quantity × Price

2.Feature Engineering
a.Grouped data by CustomerID
b.Calculated frequency, total quantity, and total spending

3.Data Standardization-Scaled features using StandardScaler for better clustering

4.Model Training (K-Means)
a.Determined optimal number of clusters (Elbow Method)
b.Trained K-Means to segment customers

5.Export Results-Final customer clusters saved to customer_segments.csv

🔍 Cluster Insights

Cluster 0: Low spending, low frequency → casual buyers
Cluster 1: High spending, frequent purchases → loyal premium customers
Cluster 2: Medium purchases, moderate spending → regular customers
Cluster 3: Rare purchases but high spending → occasional big spenders

🛠️ Tech Stack:-

Jupyter Notebook,Python
Pandas, NumPy,Matplotlib, Seaborn
Scikit-learn (KMeans, StandardScaler)

📈 Results & Business Value:-

1.Helps identify valuable customer groups
2.Enables targeted marketing campaigns
3.Improves customer retention strategies
4.Optimizes product promotions for each segment

▶️ How to Run :- 
git clone https://github.com/your-username/CustomerSegmentation.git
cd CustomerSegmentation


