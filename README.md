Introduction:
          The Titanic dataset is a popular dataset for data analysis and machine learning, containing passenger information and survival status. 
This project involves loading the dataset, handling missing data through imputation or removal, encoding categorical variables, standardizing numerical 
features, and visualizing outliers to assess their impact on analysis and modeling.

Handling Missing Data: 
          In three columns, there is missing data. The "Cabin" column has more than 50% missing values, so I dropped this column. The "Age" column has 
some missing values, which were imputed using the median. The "Embarked" column has very few missing values, which were imputed using the mode.

Encoding: 
          There are some categorical columns, and I performed encoding for only two of them. For the 'Sex' column, I used One-Hot Encoding, and for the 'Embarked' column, I applied One-Hot Encoding to create separate binary columns for each category.

Standardizing and Visualizing Outliers:   
          Except for the target variable, "Name," and the "Ticket" column, I standardized the other columns. There are no outliers in the target column, but the 
"Age" column and some other columns contain many outliers. If I were to remove these outliers, nearly half of the data would be lost, so I decided not to remove them.

Conclusion: 
          This analysis of the Titanic dataset involved handling missing data by dropping the "Cabin" column and imputing values for "Age" and "Embarked." Categorical 
variables were encoded using one-hot encoding. Most numerical features were standardized, but outliers in the "Age" column were retained to preserve data integrity. 
These preprocessing steps are essential for developing a robust predictive model and understanding survival factors on the Titanic.
