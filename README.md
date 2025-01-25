# Zeotap_Assignment
Assignment for Zeotap Data Science Internship

## Overview
This repository contains a comprehensive data science project analyzing an e-commerce transactions dataset. The project is divided into three main tasks focusing on exploratory data analysis, customer lookalike modeling, and customer segmentation.

## Dataset
The project uses three CSV files:
- `Customers.csv`: Customer profile information
- `Products.csv`: Product details
- `Transactions.csv`: Transaction records

### Data Columns
#### Customers
- CustomerID: Unique customer identifier
- CustomerName: Customer's name
- Region: Customer's continent
- SignupDate: Date of customer registration

#### Products
- ProductID: Unique product identifier
- ProductName: Product name
- Category: Product category
- Price: Product price in USD

#### Transactions
- TransactionID: Unique transaction identifier
- CustomerID: Customer who made the transaction
- ProductID: Product sold
- TransactionDate: Date of transaction
- Quantity: Number of products purchased
- TotalValue: Total transaction value
- Price: Product price

## Project Tasks

### 1. Exploratory Data Analysis (EDA)
- Performed comprehensive analysis of the e-commerce dataset
- Generated 5+ business insights
- Created visualizations and statistical summaries

### 2. Lookalike Model
- Developed a model recommending 3 similar customers based on profile and transaction history
- Generated similarity scores for customer recommendations
- Output: `Lookalike.csv` with customer similarity mappings

### 3. Customer Segmentation
- Applied clustering techniques on customer profiles and transaction data
- Explored customer segments using various clustering algorithms
- Calculated and evaluated clustering metrics, with focus on DB Index
- Visualized cluster distributions

## Deliverables
- `FirstName_LastName_EDA.pdf`: EDA report
- `FirstName_LastName_EDA.ipynb`: EDA Jupyter Notebook
- `FirstName_LastName_Lookalike.csv`: Lookalike customer recommendations
- `FirstName_LastName_Lookalike.ipynb`: Lookalike model explanation
- `FirstName_LastName_Clustering.pdf`: Clustering results report
- `FirstName_LastName_Clustering.ipynb`: Clustering analysis notebook

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib/Seaborn
- Jupyter Notebook

## Evaluation Criteria
- Model accuracy and logic
- Quality of recommendations
- Clustering metrics
- Code efficiency and insights

## Contact
Kaif Tokare
kaiftokare19@gmail.com
