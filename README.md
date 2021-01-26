# Spotify-Music-Classifier-Prediction

**Objective: "Can a song be predicted to hit the top 100 on Spotify Charts?"**

The goal of the project is to create a predictor that will classify a song as a top hit or not, and extract the features that determine such classification. Data will be scraped from spotify through their API, explored and visualized via Jupyter Notebook, modeled via a flask app, and summarized in presentation slides.

## Spotify API and Webscraping  (PART 1)
 

- Learn the Spotify API and sign up for credentials
- Write python library that will make the webscraping process easier
- Scrape the "Spotify Charts," the Top 200 most streamed songs as of late
- Scrape a user's playlist of about 1000 hits from the past decade


## EDA, Model Selection, and Feature Engineering  (PART 2)

- Combine the data into 1, clean, by removing duplicates and fixing nulls etc.
- Come up with a baseline model 
- EDA -- Analyze the pair plots and class imbalance
- Find better models, feature engineer, tune hyperparameters, and finalize model.

## Flask App Predictor & Presentation(PART 3)

- Convert the Model into an App/ Predictor
- Create a Presentation with highlighted points


## Results

**Final Model**: Random Tree Forest, classweights, SMOTE sampling, and F-Beta as a metric with a heavier weight on Precision

**Top 3 Important Features**: Duration/Dance (quick and danceable), duration (alone), and duration/acousticness ("authentic")

**Scores**: 
- ROC/AUC: .76
- FBeta: .51
- Precision: .71

