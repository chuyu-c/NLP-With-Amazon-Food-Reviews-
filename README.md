# NLP-With-Amazon-Food-Reviews


## Problem Statement
While shopping online, customers widely look for reviews and ratings(1-5) for the products, which could help in understanding the reliability of the product before they initiate a purchase. 

Key questions to address after completion of this project:  
  * Is it possible to determine the sentiment of the review?
  * What words tend to indicate positive and negative reviews?
  * What kind of reviews tend to be more helpful?
  * How is the word count related to sentiment of a review?

## Assumption
  * Given a product review, using machine learning models to determine whether the sentiment of the review is positive or negative. 
  * Use F1 Score, which balances precision and recall, as validation metrics.

## Data 
  * Amazon Fine Food Reviews https://www.kaggle.com/snap/amazon-fine-food-reviews
  * This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012.
  * Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

## Modelling
  * Ensemble models:
    * Random Forest
    * Gradient Boosting
    * XGBoost

  * Neural Network Models:
    * Convolutional Neural Network
    * Recurrent Neural Network

## Structure of the code
  1. Data Exploratory & Visualization
  2. Data Cleaning and Feature Engineering (Encoding)
  3. Random Forest & Gradient Boosting & RNN
  4. XGBoost & CNN

## Reference
1. TEXT PREPROCESSING USING PYTHON https://www.kaggle.com/shashanksai/text-preprocessing-using-python
2. Practical Text Classification With Python and Keras https://realpython.com/python-keras-text-classification/#your-first-keras-model
3. Exploratory Data Analysis https://www.kaggle.com/kanavbansal/exploratory-data-analysis
