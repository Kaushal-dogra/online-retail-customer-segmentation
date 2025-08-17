# Online Retail Dataset - Customer Segmentation  

## Introduction  
This project segments customers based on purchase behavior using **RFM analysis** and **K-Means clustering**. The aim is to help businesses understand their customer base and improve marketing strategies.  

## Technologies Used  
- Python  
- Numpy, Pandas  
- Matplotlib, Seaborn  
- scikit-learn  

## Methods  
- Data Cleaning & EDA  
- RFM Analysis  
- Feature Engineering  
- PCA & K-Means Clustering  
- Visualization & Insights  

## Data  
Transactions from **Dec 2010 – Dec 2011** of a UK-based online retail company.  
[Dataset Link](https://archive.ics.uci.edu/ml/datasets/online+retail)  

**Key Features:** InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country  

## Files  
- **Dataset** – Raw data  
- **Notebook** – Analysis & clustering workflow  
- **Assets** – Images and visuals  

## Conclusion  
Customers were successfully grouped into meaningful segments using RFM and clustering. These insights can guide targeted marketing and improve customer satisfaction.  
## summary
◦ Implemented PCA before K-Means, improving segment separation (125K–50K orders each).
◦ Optimized segmentation via RFM on 430K transactions & Elbow method, creating 4 marketing segments.
