Movie Rating Prediction with Python

Project Overview

This project aims to predict movie ratings using Machine Learning techniques in Python. It analyzes movie-related information such as genre, director, actors, duration, release year, and number of votes to estimate a movie's rating.

This project was developed as part of the Afame Technologies Data Science Internship.

Objectives

- Analyze movie data using Python.
- Clean missing values and duplicate records.
- Perform Exploratory Data Analysis (EDA).
- Visualize movie rating distributions and genre trends.
- Build a Machine Learning regression model.
- Evaluate model performance using regression metrics.
- Predict ratings for new movie data.

Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

Dataset

The project uses an IMDb Indian Movies dataset containing movie information.

Common columns include:

- "Name" — Movie title
- "Year" — Release year
- "Duration" — Movie duration
- "Genre" — Movie genre
- "Rating" — IMDb rating (target variable)
- "Votes" — Number of votes
- "Director" — Movie director
- "Actor 1", "Actor 2", "Actor 3" — Main actors

The exact columns depend on the dataset version used.

Project Workflow

1. Import required Python libraries.
2. Load the movie dataset.
3. Explore the dataset and inspect column types.
4. Handle missing values and duplicate records.
5. Convert numeric columns into appropriate data types.
6. Perform Exploratory Data Analysis.
7. Visualize rating distributions and genre trends.
8. Select input features and target variable.
9. Split the dataset into training and testing sets.
10. Encode categorical features and handle missing values.
11. Train a Random Forest Regressor.
12. Evaluate the model using MAE, RMSE, and R².
13. Predict ratings for new movie data.
14. Save the trained model and prediction results.

Machine Learning Algorithm

Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines predictions from multiple decision trees to estimate a numerical value.

In this project, it predicts movie ratings based on the selected movie features.

Model Evaluation

The model is evaluated using the following metrics:

- MAE (Mean Absolute Error): Measures the average absolute prediction error.
- RMSE (Root Mean Squared Error): Gives greater weight to larger prediction errors.
- R² Score: Measures model performance relative to a baseline that predicts the average rating.

Actual evaluation scores should be added after running the notebook.

Project Structure

Movie-Rating-Prediction/
│
├── Movie_Rating_Prediction.ipynb
├── IMDb Movies India.csv
├── movie_rating_model.pkl
├── movie_rating_predictions.csv
├── requirements.txt
└── README.md

Installation

Install the required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn joblib

How to Run

1. Download or obtain the dataset used for this project.
2. Place the CSV file in the project folder.
3. Open Jupyter Notebook.
4. Open "Movie_Rating_Prediction.ipynb".
5. Run the notebook cells in order.
6. Review the visualizations and evaluation metrics.
7. Save the trained model and prediction results.

Results

The project produces:

- Cleaned movie data.
- Exploratory data analysis visualizations.
- A trained Random Forest regression model.
- Actual versus predicted rating comparisons.
- MAE, RMSE, and R² evaluation scores.
- A saved model for future predictions.

The prediction quality depends on the dataset, feature selection, and model configuration.

Limitations

- Missing or inaccurate movie information can affect predictions.
- Ratings can be influenced by factors not included in the dataset.
- Predictions for unfamiliar directors, actors, or genres may be less reliable.
- The model estimates ratings and does not guarantee actual audience ratings.

Future Improvements

- Compare Random Forest with Linear Regression and other regression algorithms.
- Improve feature engineering.
- Tune model hyperparameters.
- Develop
