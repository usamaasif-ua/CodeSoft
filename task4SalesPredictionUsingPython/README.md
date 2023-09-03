📊 Sales Prediction Using Machine Learning!📈

Sales prediction is a pivotal aspect of any business, and I'm thrilled to share the journey of my recent project where i harnessed the power of data science and machine learning to forecast sales. I predict sales based on various factors like advertising expenditure and advertising platform selection.

Kaggle Data Set Link: https://www.kaggle.com/datasets/ashydv/advertising-dataset

🔍 Here's a glimpse of what i've accomplished:

👩‍💻 Data Preparation:
I started by importing essential libraries and loading my dataset. The dataset contained information about TV, Radio, Newspaper advertising budgets, and Sales in thousands of units.

💼 Data Overview:
I conducted an in-depth exploration of the dataset, which revealed:

200 rows of data
4 features: TV, Radio, Newspaper, and Sales
No missing values
Unique values for each feature

📊 Exploratory Data Analysis:
I performed exploratory data analysis (EDA) to understand relationships and outliers. Notably, i found:

A strong linear relationship between TV and Sales
A weaker relationship with Radio and an even weaker one with Newspaper

📈 Correlation Analysis:
My analysis highlighted that TV had the highest correlation with Sales, making it a crucial predictor.

🛠️ Feature Engineering:
I prepared my data by separating predictors (X) and the target variable (y) for model building.

🏗️ Model Building:
I constructed a predictive model using a pipeline that included standard scaling and the SGDRegressor algorithm. my model achieved impressive results:

Mean Absolute Error (MAE): 1.62
Mean Squared Error (MSE): 4.72
R-squared (R²): 0.87

🚀 Model Deployment:
I created a simple deployment feature that takes user input for advertising budgets and predicts sales.

📈 With these insights and the predictive power of my model, businesses can optimize their advertising strategies, allocate budgets effectively, and maximize their sales potential.

Let's continue exploring the fascinating world of data science and machine learning to drive growth and success. If you have any questions or want to discuss this project further, feel free to reach out! 👨‍💼📊🚀 
