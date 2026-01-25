## 📊 Dataset Information
The primary dataset used in this analysis contains over 500,000 rows of transaction data. Due to GitHub's file size limitations, the raw CSV file is not included in this repository.
### How to access the data:
- **Raw Data Source:** You can find the original dataset on [Kaggle - E-Commerce Data](https://www.kaggle.com/datasets/carrie1/ecommerce-data) .
- **Data Description:** The dataset includes real-world transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based non-store online retail.
### Data Processing Steps:
In the provided notebook, I performed the following:
1. **Cleaning:** Removed rows with missing `CustomerID` and handled negative `Quantity` values (returns).
2. **Transformation:** Converted `InvoiceDate` to a proper datetime format.
3. **Feature Engineering:** Created `Sales` and `Profit` columns for deeper financial analysis.
