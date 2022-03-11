# Book Recommender

## Exploratory Data Analysis + Data Visualization + Modelling 

### 1 - Abstract

In this project I made Exploratory Data Analysis, Data Visualisation and lastly Modelling. Dataset contains 11123 rows in csv file. Each example row represent a book with 12 different information. Before modelling part I have to check NaN values and make some small adjustment for easy to use of the dataset and merge couple of languages on 1 language(en-AUS,en-UK to eng). Later I made couple of visualization to understand the dataset better. In modelling part, I used unsupervised learning algorithm K-means which is grouping unlabelled data. For deciding number of cluster I used Elbow method and decide to do 5 clusters. Finally, I test my model with several books and add input function for searching easily. 

### 2 - Data
<a href="https://www.kaggle.com/jealousleopard/goodreadsbooks">Dataset</a> contains 12 columns and 11123 rows.

Columns Description:
* __bookID__ = contains the unique ID for each book/series
* __title__ = contains the titles of the books
* __authors__ = contains the author of the particular book
* __average_rating__ = the average rating of the books, as decided by the users
* __ISBN ISBN(10)__ = number, tells the information about a book - such as edition and publisher
* __ISBN 13__ = the new format for ISBN, implemented in 2007. 13 digits
* __language_code__ = tells the language for the books
* __Num_pages__ = contains the number of pages for the book
* __Ratings_count__ = contains the number of ratings given for the book
* __text_reviews_count__ = has the count of reviews left by users
* __publication_date__ = date of publication
* __publisher__ = name of the publisher

<p align="center">
  <img width="500" height="500" src="">
</p>
<p align="center">
     <b>Train Dataset Example</b>
</p>

### 3 - Exploratory Data Analysis

Firstly, I checked data, which came two different dataset which are train and test. Later I checked distribution of labels in datasets and I create a list for expressing images for both datasets, moreover I see all the classes(labels) equally distributed. So I dont need to do Oversampling or Undersampling. 

### 4 - Data Preprocessing


### 5 - Modelling 


### 6 - Result & Future Work

As a result, my model gives overally good results. 

