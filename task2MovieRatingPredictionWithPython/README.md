🎬 MOVIE RATING PREDICTION PROJECT 🎬

Kaggle Dataset Link: https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies?datasetId=1416444

I’m thrilled to share the amazing journey of my Movie Rating Prediction project! 📊 Here are the main steps I’ve followed and the impressive results I’ve achieved:

Importing Essential Libraries To start off, I used some essential libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn. These powerful tools helped me to analyze and manipulate the data.

Data Preprocessing Next, I loaded the IMDb movie dataset using Pandas and explored its basic characteristics. I checked its shape, missing values, and unique values for each feature.

Visualizing Insights Visualization was a key step in understanding the data better. Using Matplotlib and Seaborn, I created some interesting visualizations such as box plots, distribution plots, and scatter plots. These graphics revealed some patterns and relationships among the features.

Crafting Features Then, I prepared the dataset for the modeling stage. I decided to drop some columns that were not relevant for the prediction task, such as ‘Genre’, ‘Director’, ‘Actor 1’, ‘Actor 2’, and ‘Actor 3’. I also removed the missing data from important features such as ‘Name’, ‘Year’, ‘Duration’, ‘Votes’, and ‘Rating’.

Data Transformation and Scaling To make the data suitable for the predictive model, I performed some transformations on the features. I converted the ‘Year’ column into an integer by removing the parentheses, I removed the commas from the ‘Votes’ column, and I stripped the ‘min’ from the ‘Duration’ column.

Exploring Model Possibilities The core of the project was to build a predictive model. I chose to use a pipeline that combined Standard Scaling with the SGD Regressor. This pipeline simplified the modeling process and integrated data preprocessing smoothly.

Validating Model Performance The final step was to evaluate how well the pipeline performed on predicting movie ratings. I used some metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. These metrics showed how accurate and reliable the pipeline was.

A Glimpse into the Future As a bonus, I demonstrated how the trained pipeline can easily predict movie ratings for new user inputs. The future holds many opportunities to improve and enhance this predictive project.

This project was a great learning experience for me. I enjoyed exploring, visualizing, crafting, modeling, and evaluating the data. Join me in discovering the secrets and magic of movie rating prediction through machine learning models. 🚀