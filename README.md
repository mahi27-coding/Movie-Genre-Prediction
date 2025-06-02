# Movie Genre Prediction using NLP

This project is part of the CodeClause Data Science Internship. The goal is to predict the genre of a movie using its plot summary. It uses Natural Language Processing (NLP) techniques along with machine learning algorithms to perform text classification.

## Project Details

- Project ID: #CC69848  
- Internship Domain: Data Science  
- Project Level: Intermediate  
- Technologies Used: Python, NLTK, SpaCy, Scikit-learn  
- Dataset Used: movie_plots_cleaned.csv

## Objective

To develop a machine learning model that can predict the genre of a movie based on its plot summary using natural language processing techniques.

## What You Will Learn

- How to clean and preprocess text using NLTK  
- How to convert text into numerical features using TF-IDF  
- How to train and evaluate a Naive Bayes classifier  
- How to predict the genre of new movie plots  
- How to visualize data and model performance

## How to Run This Project

1. Open the file `Movie_Genre_Prediction_CodeClause.ipynb` in Google Colab or Jupyter Notebook.  
2. Upload the `movie_plots_cleaned.csv` dataset when prompted.  
3. Run each cell step-by-step to see the output.  
4. Use the `predict_genre()` function to test the model with your own plot summary.

## Files Included

- `Movie_Genre_Prediction_CodeClause.ipynb` – Main notebook containing all steps  
- `movie_plots_cleaned.csv` – Dataset used for training  
- `requirements.txt` – List of Python libraries used in the project

## Sample Prediction

```python
plot = "A man discovers he is living in a simulated reality and fights back."
predict_genre(plot)
