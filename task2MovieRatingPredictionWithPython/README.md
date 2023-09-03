🎬 Movie Rating Prediction Using Machine Learning 🎬

I’m happy to share my amazing project on movie rating prediction using machine learning. As you may know, movie rating prediction is a fascinating task that can help movie lovers and critics to discover new movies and rate them based on their preferences. My goal for this project was to build a machine learning model that can predict movie ratings based on various features such as genre, director, actors, year, duration, and votes.

Dataset link: [https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies?datasetId=1416444]

Key Steps and Highlights: 

📊 Data Importing: I used the IMDb movie dataset from Kaggle as my data source. I imported some essential libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn to analyze and manipulate the data.

🔍 Data Preprocessing: I explored the basic characteristics of the dataset, such as its shape, missing values, and unique values for each feature. I decided to drop some columns that were not relevant for the prediction task, such as ‘Genre’, ‘Director’, ‘Actor 1’, ‘Actor 2’, and ‘Actor 3’. I also removed the missing data from important features such as ‘Name’, ‘Year’, ‘Duration’, ‘Votes’, and ‘Rating’.

🤖 Data Visualization: Visualization was a key step in understanding the data better. Using Matplotlib and Seaborn, I created some interesting visualizations such as box plots, distribution plots, and scatter plots. These graphics revealed some patterns and relationships among the features.

📈 Feature Engineering: To make the data suitable for the predictive model, I performed some transformations on the features. I converted the ‘Year’ column into an integer by removing the parentheses, I removed the commas from the ‘Votes’ column, and I stripped the ‘min’ from the ‘Duration’ column.

🔄 Data Transformation and Scaling: To ensure an unbiased modeling process, I applied Standard Scaling to the features.

💡 Model Building: The core of the project was to build a predictive model. I chose to use a pipeline that combined Standard Scaling with the SGD Regressor, a popular supervised learning algorithm that can learn from the data and make predictions.

📊 Model Evaluation: The final step was to evaluate how well the pipeline performed on predicting movie ratings. I used some metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. These metrics showed how accurate and reliable the pipeline was.

🚀 Model Deployment: As a bonus, I demonstrated how the trained pipeline can easily predict movie ratings for new user inputs. The future holds many opportunities to improve and enhance this predictive project.

Why Movie Rating Prediction Matters: By predicting movie ratings based on various features, movie lovers and critics can discover new movies and rate them based on their preferences. This data-driven approach can lead to enhanced movie enjoyment and satisfaction.

I’m thrilled with the insights I’ve gained from this project and the potential impact it could have on movie enthusiasts and reviewers. Join me in discovering the secrets and magic of movie rating prediction through machine learning models. 🚀
