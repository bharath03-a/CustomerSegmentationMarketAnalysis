# Customer Segmentation Project:

<p align="center">
  <img src="https://towardsdatascience.com/wp-content/uploads/2019/01/1z55Hi1HtLpdBhhPQbS9rZQ.gif" alt="uci" height="150">
</p>

## Overview
This project leverages transactional data from a UK-based non-store online retail company to perform **customer segmentation** using data mining techniques. The goal is to identify meaningful customer groups by analyzing purchasing behaviors, using features like transaction frequency, spending patterns, and product preferences.

The dataset spans transactions between **December 1, 2010**, and **December 9, 2011**, and consists of purchase history data for customers, product details, and transaction information.

---

## Dataset Information
- **Dataset Name**: Online Retail Dataset  
- **Source**: Transactional data for a UK-based non-store online retail company  
- **Size**: 541,909 transactions  
- **Features**: 6 features (categorical and numerical)  
- **Temporal Span**: December 1, 2010 - December 9, 2011  

---

## Dataset Features  

The dataset contains the following features:

| **Variable Name** | **Role**   | **Type**       | **Description**                                   |  
|--------------------|-------------|----------------|--------------------------------------------------|  
| **InvoiceNo**      | ID           | Categorical   | A 6-digit number uniquely assigned to each transaction. (Codes starting with 'c' indicate cancellation) |  
| **StockCode**      | ID           | Categorical   | A 5-digit number uniquely assigned to each product |  
| **Description**    | Feature      | Categorical   | Product name                                      |  
| **Quantity**       | Feature      | Integer       | Number of products in each transaction            |  
| **InvoiceDate**     | Feature      | Date/Time     | Date and time of each transaction                 |  
| **UnitPrice**      | Feature      | Continuous    | Price per unit of product (in sterling)          |  
| **CustomerID**     | Feature      | Categorical   | A unique 5-digit identifier for each customer    |  
| **Country**        | Feature      | Categorical   | Country where the customer resides               |  

---

## Objectives
The main goals of this project are to:

1. **Understand Customer Behavior**: Analyze purchasing frequency, spending patterns, and product preferences over time.
2. **Perform Segmentation**: Apply clustering techniques (e.g., K-Means, DBSCAN, or RFM analysis) to segment customers into distinct groups based on transaction behavior.
3. **Identify Key Patterns**: Explore patterns like high-frequency purchases, high spending, seasonal trends, and product preferences.
4. **Build Insights**: Extract actionable insights from customer clusters to inform marketing strategies, inventory management, and targeted offers.

---

## Key Tasks
1. **Data Preprocessing**:
   - Handle any inconsistencies or incorrect data entries (even though the data has no missing values).
   - Transform categorical features into numerical representations if necessary.
   - Prepare time-series features for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of transactions, frequency of purchases, and other temporal trends.
   - Understand customer demographics and transaction trends by country and product category.

3. **Customer Segmentation Modeling**:
   - Use clustering techniques such as K-Means, DBSCAN, or hierarchical clustering to segment customers.
   - Segment customers based on recency, frequency, monetary value (RFM), or other relevant features.

4. **Validation & Interpretation**:
   - Validate the identified customer clusters for business value.
   - Interpret the segmentation results to generate insights.

5. **Visualization**:
   - Use visualization tools (e.g., Tableau, matplotlib, seaborn) to communicate key findings.

---

## Data Analysis Tools & Technologies
The following tools and libraries will be used throughout the project:

- **Python Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
- **Data Visualization Tools**: `Tableau`, `matplotlib`, `seaborn`
- **Clustering Algorithms**: K-Means, DBSCAN, Hierarchical Clustering
- **Data Processing**: pandas, NumPy
- **Time-Series Analysis**: pandas time-based indexing  

---

## Dependencies
You will need the following Python packages:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
