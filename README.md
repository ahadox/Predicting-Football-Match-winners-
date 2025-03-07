# English Premier League Match Winner Prediction

## Project Overview
This project aims to predict the winners of football matches in the English Premier League (EPL) using machine learning techniques. We scrape historical match data, clean and preprocess it, build predictive models, and evaluate their performance to improve accuracy.

## Project Steps
1. **Scrape Match Data**: Use `requests`, `BeautifulSoup`, and `pandas` to scrape EPL match data from FBref.
2. **Clean and Preprocess Data**: Process and format the scraped data to make it suitable for machine learning.
3. **Make Predictions**: Train models using `scikit-learn` to predict match outcomes.
4. **Evaluate and Improve Model**: Measure errors, refine features, and optimize model performance.

## Repository Structure
- `scraping.ipynb` – Jupyter notebook for web scraping match data.
- `predictions.ipynb` – Jupyter notebook for training and testing the prediction model.
- `matches.csv` – Dataset containing EPL match statistics.

## Project Workflow
1.Web Scraping & Data Collection
- Fetch match stats using requests.
- Parse and extract data using BeautifulSoup.
- Organize scraped data into a structured pandas DataFrame.

2.Data Cleaning & Feature Engineering
- Handle missing values and inconsistencies.
- Generate predictor variables for machine learning.

3.Machine Learning Model
- Train an initial prediction model using scikit-learn.
- Improve model performance with rolling averages.
- Combine home and away match features to refine predictions.

