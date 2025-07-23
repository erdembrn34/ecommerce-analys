E-Commerce Customer Segmentation
Project Overview
This project analyzes customer purchase behavior in an e-commerce setting to identify distinct customer segments using RFM (Recency, Frequency, Monetary) analysis and clustering techniques. The goal is to gain actionable insights for targeted marketing and personalized customer engagement.

Dataset
The dataset consists of 300 simulated customer transactions with the following fields:

CustomerID: Unique identifier for each customer

OrderDate: Date of the purchase

OrderAmount: Monetary value of the order

ProductCategory: Category of the purchased product (Electronics, Clothing, Home, etc.)

PaymentMethod: Payment channel used (Credit Card, PayPal, Bank Transfer, Cash)

Region: Customer's geographical region

Frequency: Purchase frequency indicator

Recency: Days since the last purchase

Analysis Steps
Data Cleaning and Preprocessing
Conversion of date fields, checking for missing values, and data consistency validation.

Exploratory Data Analysis (EDA)
Visualization and summary statistics of product categories, payment methods, regional distribution, order amounts, frequency, and recency.

RFM Feature Engineering
Calculation of Recency, Frequency, and Monetary values aggregated at the customer level.

Customer Segmentation
Application of K-Means clustering on standardized RFM values to segment customers into meaningful groups.

Segment Profiling
Analysis of segment characteristics and visualization of key metrics per segment.

Tools and Libraries
Python

Pandas

Matplotlib

Seaborn

Scikit-learn

How to Run
Clone the repository or download the dataset (ecommerce_customer_data.csv).

Install dependencies:
pip install pandas matplotlib seaborn scikit-learn
Run the analysis notebook or script to reproduce the results and visualizations.

Conclusion
This segmentation helps businesses understand customer behavior, optimize marketing strategies, and improve customer retention by targeting specific customer groups effectively.


