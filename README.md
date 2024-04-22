# Analysis-of-store-ssales
Linear Regression on Different Stores Sales
Data analysis project related to sales data from different stores

# Actions Performed

- Data Import and Preprocessing: Start by importing the necessary packages and loading the dataset from a CSV file named "Different_stores_dataset.csv." Then I create a new column called "totalsales" by multiplying the quantity of items sold by their selling price per unit. The dataset is examined for missing values and duplicates.

- Exploratory Data Analysis (EDA): Conduct EDA by visualizing various aspects of the data using histograms and bar plots. This includes analyzing the distribution of age, total sales per unit, payment methods, category, selling price per unit, and cost price per unit. Additionally, I investigated sales divided by region and the popularity of different product categories.

- Hypothesis Testing: I performed hypothesis tests to analyze significant differences in spending between men and women, purchasing behaviors among different age groups, and the total purchase amount influenced by different payment methods.

- Linear Regression Modeling (LRM):  Prepare data for linear regression modeling by renaming columns, converting categorical variables to numerical, and selecting relevant variables. Then,  build several linear regression models including a full model, base model, backward model, forward model, stepwise model, and best subset model. Residual analysis and normality tests are conducted to evaluate model assumptions.

-Advanced Techniques in LRM: Advanced techniques such as variance inflation factor (VIF) analysis, identifying influential data points, and assessing multicollinearity are performed to improve model accuracy and reliability.

-Evaluation of Models: The performance of each model is evaluated using root mean square error (RMSE) on a test dataset.

-Second Linear Regression Modeling (LRM2): You repeat a similar process of data preparation, model building, and evaluation for a different response variable, "sellingppu."
