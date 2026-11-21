# Supermarket Sales – Exploratory Data Analysis (EDA)

## 1. Project Title
**Supermarket Sales – Exploratory Data Analysis (EDA)**

## 2. Project Description
This project focuses on analyzing supermarket sales data to understand sales performance, customer purchasing behavior, product preferences, and revenue patterns.

The main objective is to perform Exploratory Data Analysis (EDA), identify meaningful patterns, create visualizations, and generate business insights with practical recommendations.

## 3. Dataset Information
- **Dataset:** Supermarket Sales Dataset
- **Total Records:** 1,000
- **Total Features:** 17
- **Time Period:** January – March 2019
- **Branches:** 3
- **Dataset Source:** [GitHub – Supermarket Sales](https://github.com/selva86/datasets/blob/master/supermarket_sales.csv)

The dataset contains information about:
- Branch and City
- Customer Type and Gender
- Product Line
- Unit Price and Quantity
- Tax and Total Sales
- Date and Time
- Payment Method
- Cost of Goods Sold (COGS)
- Gross Income
- Customer Rating

## 4. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 5. Analysis Performed
- Data loading and initial inspection
- Missing values and duplicate records analysis
- Data type conversion and consistency checking
- Numerical and categorical feature analysis
- Descriptive statistical analysis
- Correlation analysis
- Creation of 12+ meaningful visualizations
- Identification of business insights
- Development of business improvement recommendations

## 6. Key Findings
- Quantity has a strong positive correlation (approximately 0.71) with Total, Tax 5%, COGS, and Gross Income.
- Product-line analysis helps identify high- and low-performing categories.
- Branch comparisons reveal differences in sales performance.
- Customer analysis provides insights into purchasing behavior.
- Payment analysis identifies popular payment methods.
- Customer ratings help evaluate satisfaction across product categories.
- Daily and monthly sales analysis reveals revenue patterns.

## 7. Business Recommendations
- Apply successful sales strategies from high-performing branches to lower-performing branches.
- Focus marketing efforts on high-revenue product lines.
- Investigate and improve low-performing product categories.
- Use customer spending patterns to develop targeted promotions.
- Optimize inventory according to product demand.
- Improve customer satisfaction by investigating lower-rated categories.
- Introduce product bundles and cross-selling strategies to increase transaction value.

## 8. Instructions to Run the Notebook

**Step 1: Clone the Repository**
```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2: Open the Project Folder**
```bash
cd supermarket-sales-eda
```

**Step 3: Install Required Libraries**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Step 4: Launch Jupyter Notebook**
```bash
jupyter notebook
```

**Step 5: Run the Notebook**

Open the `.ipynb` file in Jupyter Notebook and execute all cells sequentially.

**Note:** The dataset is loaded directly from GitHub through the notebook, so you do not need to download it separately, provided the dataset URL remains accessible.
