# restaurant-business-analytics

**Restaurant Sales Exploratory Data Analysis**

**Project Overview**

This project performs exploratory data analysis (EDA) on restaurant billing and sales data to understand revenue patterns, customer spending behavior, and top-selling menu items.

**Dataset Description**
The analysis uses two CSV files:

- **i1.csv** – Invoice-level billing data
- **i2.csv** – Item-level sales data

After merging both datasets, the final data contains:

- **Invoice No.** – unique invoice identifier  
- **Item Name** – menu item name  
- **Qty.** – quantity sold  
- **Final Total** – revenue amount  
- **Date** – transaction date  


##**Data Cleaning and Checks**
Basic data checks include:

- **Dataset shape and structure**
- **Data types and summary statistics**
- **Missing value analysis**

**Key Analysis Performed**

- **Total revenue and average bill value per invoice**
- **Count of unique invoices**
- **Top-selling items by quantity**
- **Top revenue-generating items**
- **Top-selling item for each date**
- **High-spend invoices compared to average bill value**
- **Relationship between quantity sold and revenue**
- **Item contributing the highest percentage of total revenue**

**Tools and Libraries Used**

- **Python**
- **pandas**
- **numpy**
- **matplotlib**

**How to Run the Project**
Clone the repository:
git clone https://github.com/your-username/restaurant-sales-eda.git

Then:
- **Open the notebook in Jupyter Notebook or Google Colab**
- **Update the dataset file paths if required**
- **Run all cells sequentially**


##**Conclusion**
The analysis shows that items with high sales quantity do not always generate high revenue, highlighting the importance of pricing strategy along with demand.
