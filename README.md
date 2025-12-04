**Dataset Overview**

The dataset contains 1000 transaction entries from a supermarket with these key attributes:

Features include:

Invoice ID
Branch (A, B, C)
City (Yangon, Mandalay, Naypyitaw)
Customer Type (Member / Normal)
Gender
Product Line
Unit Price
Quantity
Tax (5%)
Total
Date & Time
Payment Method (Cash, Ewallet, Credit Card)
COGS
Gross Income
Rating

**Data Preparation**

In the notebook, I performed:

Loaded the CSV using pandas
Checked data shape → 1000 rows × 17 columns
No missing values
Converted Date to datetime
Generated statistical descriptions (describe())

**Analysis & Visualizations**

The notebook includes multiple visualizations and statistical summaries:

1.Gender Distribution

Count of Male vs Female customers
sns.countplot(x=df['Gender'])

2.Customer Ratings Distribution

Rating histogram using seaborn

3.Transactions per Branch

Branches A, B, C transaction counts

df["Branch"].value_counts()

4.Popular Payment Methods

Ewallet → 345
Cash → 344
Credit Card → 311
Stacked bar chart by branch included.

5.Customer Ratings by Branch

Boxplot to compare satisfaction levels.

6.Gross Income Analysis

Gross income by branch
Gross income by gender
Daily gross income trend over time
Branch C produced the highest gross income.

**Key Insights**

Gender distribution is equal → 501 Female, 499 Male.
Branch C generated the highest total gross income.
Ewallet was slightly more preferred than Cash and Credit Card.
Ratings are generally positive, consistent across branches.
Product lines like Fashion accessories, Electronics, Health & Beauty contribute heavily to revenue.
Female customers have slightly higher average gross income contribution.

**Language & Library Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

**How to Run**

Clone the repository:
git clone https://github.com/yourusername/SuperMarketAnalysis.git

Install required packages:
pip install pandas numpy matplotlib seaborn


**Open the notebook:**
jupyter notebook SuperMarket.ipynb

**Future Improvements**
Add predictive modeling (sales forecasting)
Customer segmentation using clustering
Build a dashboard using PowerBI/Streamlit/Plotly
Product-line based revenue forecasting

**Contributing**

Pull requests are welcome!
Feel free to add more analysis, visualizations, or improvements.

**If You Found This Useful**

Give this repository a star to support more data analysis projects like this!
