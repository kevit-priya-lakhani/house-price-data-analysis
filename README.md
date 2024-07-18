# house-price-data-analysis
# House Price Data Analysis

## Dataset: House Prices

The dataset used for this analysis is the House Prices dataset available on Kaggle. You can access the dataset [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## Tools and Libraries Used
- Google Colab: Python environment for data analysis and machine learning.
- NumPy: Library for numerical computing in Python.
- pandas: Library for data manipulation and analysis.
- Matplotlib and Seaborn: Libraries for data visualization.

## Analysis Steps

### NumPy

1. **LotArea Analysis:**
   - Created a NumPy array for the "LotArea" column and calculated its mean, median, and standard deviation.

2. **SalePrice Normalization:**
   - Normalized the "SalePrice" column using Min-Max scaling.

### pandas

1. **Data Loading:**
   - Loaded the dataset into a pandas DataFrame.

2. **Summary Statistics:**
   - Displayed summary statistics for the dataset including count, mean, standard deviation, min, max, and quartiles.

3. **Handling Missing Values:**
   - Imputed missing values in columns appropriately, using mean, median, or mode as applicable.

4. **Categorical Variable Encoding:**
   - Applied one-hot encoding to categorical variables in the dataset.

5. **Feature Engineering:**
   - Created a new column "Age" representing the age of houses at the time of sale by calculating the difference between "YrSold" and "YearBuilt".

6. **Neighborhood Analysis:**
   - Grouped data by "Neighborhood" and calculated the average sale price for each neighborhood.

### Exploratory Data Analysis (EDA)

1. **Distribution of SalePrice:**
   - Plotted the distribution of the "SalePrice" column to visualize its spread and skewness.

2. **Relationship Between GrLivArea and SalePrice:**
   - Created a scatter plot to show the relationship between "GrLivArea" (above ground living area) and "SalePrice".

3. **Correlation Analysis:**
   - Plotted a correlation matrix to identify the top 5 features most correlated with "SalePrice".

4. **Average Sale Price by OverallQual:**
   - Plotted average sale prices grouped by the overall quality of houses ("OverallQual").

5. **Box Plots of SalePrice by Building Type:**
   - Created box plots to visualize the distribution of "SalePrice" across different building types ("BldgType").

## Conclusion

This project provided insights into the house price data, including key statistics, relationships between variables, and factors influencing sale prices. Further machine learning models or advanced analytics can be applied for prediction and deeper insights.
