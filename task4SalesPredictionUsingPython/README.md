📊 Sales Prediction Using Machine Learning!📈

Sales prediction is a pivotal aspect of any business, and I'm thrilled to share the journey of our recent project where we harnessed the power of data science and machine learning to forecast sales. In this project, we aimed to predict the quantity of products customers would purchase, taking into consideration various factors like advertising expenditure, target audience segmentation, and advertising platform selection.

Kaggle Data Set Link: https://www.kaggle.com/datasets/ashydv/advertising-dataset
🔍 Here's a glimpse of what we've accomplished:

👩‍💻 Data Preparation:
We started by importing essential libraries and loading our dataset. The dataset contained information about TV, Radio, Newspaper advertising budgets, and Sales in thousands of units.

💼 Data Overview:
We conducted an in-depth exploration of the dataset, which revealed:

200 rows of data
4 features: TV, Radio, Newspaper, and Sales
No missing values
Unique values for each feature
📊 Data Analysis:
We performed exploratory data analysis (EDA) to understand relationships and outliers. Notably, we found:

A strong linear relationship between TV and Sales
A weaker relationship with Radio and an even weaker one with Newspaper
📈 Correlation Analysis:
Our analysis highlighted that TV had the highest correlation with Sales, making it a crucial predictor.

🛠️ Feature Engineering:
We prepared our data by separating predictors (X) and the target variable (y) for model building.

🏗️ Model Building:
We constructed a predictive model using a pipeline that included standard scaling and the SGDRegressor algorithm. Our model achieved impressive results:

Mean Absolute Error (MAE): 1.62
Mean Squared Error (MSE): 4.72
R-squared (R²): 0.87
🚀 Model Deployment:
We even created a simple deployment feature that takes user input for advertising budgets and predicts sales. Just input the budgets for TV, Radio, and Newspaper, and our model will predict your potential sales.

📈 With these insights and the predictive power of our model, businesses can optimize their advertising strategies, allocate budgets effectively, and maximize their sales potential.

Let's continue exploring the fascinating world of data science and machine learning to drive growth and success. If you have any questions or want to discuss this project further, feel free to reach out! 👨‍💼📊🚀 