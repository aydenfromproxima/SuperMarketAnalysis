# Supermarket Sales Analysis

A comprehensive exploratory data analysis (EDA) of 1,000 supermarket transactions, uncovering customer behavior, payment trends, revenue drivers, and branch-level performance.

---

## Dataset Overview

The dataset includes 1,000 transaction entries with the following attributes:

- Invoice ID  
- Branch (A, B, C)  
- City (Yangon, Mandalay, Naypyitaw)  
- Customer Type (Member / Normal)  
- Gender  
- Product Line  
- Unit Price  
- Quantity  
- Tax (5%)  
- Total  
- Date & Time  
- Payment Method (Cash, Ewallet, Credit Card)  
- COGS  
- Gross Income  
- Rating  

---

## Data Preparation

- Loaded CSV using pandas  
- Verified shape: **1000 × 17**  
- Confirmed **no missing values**  
- Converted Date column to datetime  
- Produced descriptive statistics using `.describe()`  

---

## Analysis & Visualizations

### 1. Gender Distribution
Countplot comparing Male vs Female customers.

### 2. Customer Ratings Distribution
Histogram showing rating distribution.

### 3. Transactions per Branch
Transaction counts for branches A, B, and C.

### 4. Popular Payment Methods
- Ewallet: 345  
- Cash: 344  
- Credit Card: 311  

Includes a stacked bar chart by branch.

### 5. Customer Ratings by Branch
Boxplot comparing customer satisfaction across branches.

### 6. Gross Income Analysis
- Gross income by branch  
- Gross income by gender  
- Daily gross income trend  
- **Branch C** showed the highest total gross income  

---

## Key Insights

- Customers are evenly split: **501 Female, 499 Male**  
- Branch C generated the highest gross income  
- Ewallet was slightly more preferred than Cash and Credit Card  
- Ratings were consistently positive across branches  
- Fashion Accessories, Electronics, and Health & Beauty were top revenue-generating product lines  
- Female customers contributed slightly higher average gross income  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## How to Run

### Clone the repository:
bash
```git clone https://github.com/yourusername/SuperMarketAnalysis.git```
### Install dependencies:
bash
Copy code
pip install pandas numpy matplotlib seaborn
### Open the notebook:
bash
Copy code
jupyter notebook SuperMarket.ipynb

---

### Future Improvements
Add predictive modeling (sales forecasting)

Customer segmentation via clustering

Build a dashboard using PowerBI, Streamlit, or Plotly

Product-line based revenue forecasting

---

## Contributing
Pull requests are welcome.
Feel free to submit improvements, visualizations, or new analyses.

---

## Support
If you found this project useful, consider giving the repository a star.
