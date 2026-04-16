# Airline Passenger Sentiment: From Web Scraping to Predictive Modeling ✈️📊

## Project Overview
This project delivers an end-to-end Machine Learning pipeline designed to understand and predict passenger satisfaction. By scraping real-world data from over 10 major airlines (including Aegean, Emirates, and Lufthansa), the system processes natural language reviews to classify customer sentiment as Positive or Negative.

## The Workflow
1. **Data Acquisition (Web Scraping):** Developed a custom scraper using `BeautifulSoup` and `Requests` to bypass pagination and extract review text, ratings, and metadata from Skytrax.
2. **Text Preprocessing:** Cleaned and vectorized unstructured text data using `CountVectorizer`, removing noise and common stopwords to focus on impactful keywords.
3. **Sentiment Labeling:** Engineered a binary sentiment feature based on passenger ratings (Threshold: Rating > 5 = Positive).
4. **Machine Learning & Optimization:** * Implemented and compared **Naive Bayes** and **Decision Tree** classifiers.
    * Utilized **GridSearchCV** for hyperparameter tuning to maximize model accuracy and F1-score.

## Key Technical Skills
* **Web Scraping:** `BeautifulSoup`, `Requests`, Handling pagination & headers.
* **Natural Language Processing (NLP):** Text cleaning, Tokenization, Vectorization.
* **Supervised Learning:** Classification, Model Evaluation (Precision/Recall/F1).
* **Optimization:** Cross-Validation, Grid Search.

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** `Pandas`, `NumPy`, `Scikit-learn`, `BeautifulSoup4`, `Matplotlib`.

## Project Structure
* `scraper.py`: The script used to generate the dataset.
* `sentiment_analysis.py`: The core ML pipeline (Preprocessing, Training, Evaluation).
* `reviews.csv`: The final processed dataset used for modeling.

## Strategic Insight
This tool allows airline operators to automate the monitoring of brand reputation and identify specific pain points in the passenger experience through automated text classification.

---
**Author:** Athina Stavropoulou  
**Contact:** www.linkedin.com/in/athinastavropoulou
