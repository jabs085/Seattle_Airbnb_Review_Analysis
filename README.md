# Seattle_AirBnB_Analysis

## Motivation
This is an attempt to understand what impacts the reviews of a listing. 
In other words, what features in a listing determines a high rating 
and what can Airbnb listers do to improve them. The following four questions was
an attempt in doing so:

> 1. Are there any significant correlations in the data?
> 2. Can we predict the review score?
> 3. What features impact the review rating?
> 4. What are the customers saying about high/low rating listings and is there any
insight to what impacted review scores.

---

## Libraries on python3

* matplotlib
  * pyplot
* numpy
* pandas
* seaborn
* nltk
  * tokenize.word_tokenize 
  * sentiment.vader.SentimentIntensityAnalyzer
  * corpus.names
* sklearn
  * ensemble.RandomForestClassifier
  * metrics.accuracy_score
  * model_selection.train_test_split
  * preprocessing.MinMaxScaler
* wordcloud
  * STOPWORDS
  * WordCloud

## Contents

### Data
 * calendar.csv - Availability data for 2016
 * listings.csv - Listing details, host information along with review data.
 * reviews.csv - Listing reviewer information along with comment left from reviewer.

### Notebooks
 * Seattle_AirBnB_Review_Analysis - A light analysis on review scores from the Seattle AirBnB dataset.

### Summary


The completed analysis is suspect to my experience, which may have led to less than optimal decisions. Nonetheless, I feel confident in the completed notebook and believe this can help those who are just getting started in data science or are considering listing on Airbnb.

1. Detected Correlated features 

2. Successfully predicted the review rating. 

3. Enumerated critical features to predict the rating. Thereby, finding what is important to the customers. 

4. In order to get a better idea of what makes these reviews tick I generated a word cloud for each type of review (Positive, negative). 

