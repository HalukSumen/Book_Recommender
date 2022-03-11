# Book Recommender

## Exploratory Data Analysis + Data Visualization + Modelling 

### 1 - Abstract

In this project I made Exploratory Data Analysis, Data Visualisation and lastly Modelling. Fashion Mnist Dataset contains 70000 row in two files. Each example is 28x28 image and associated with __10__ labels(targets). After examining the dataset I made data preprocessing for reshaping columns from __784__ to __(28,28,1)__ and save the target feature as a seperate vector. In modelling part, with a sequential model with multiple convolution layers with __50__ Epochs for training the data. For prediction overfitting and underfitting I adjust Dropout Layers. Overally, model gives __0.9236__ accuracy. Furthermore with Data augmentation and/or incresing data size can be helpful for taking better result. 

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
  <img width="500" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/train%20data%20example.png">
</p>
<p align="center">
     <b>Train Dataset Example</b>
</p>

<p align="center">
  <img width="500" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/test%20data%20example.png">
</p>
<p align="center">
   <b>Test Dataset Example</b>
</p>

### 3 - Exploratory Data Analysis

Firslty, I checked data, which came two different dataset which are train and test. Later I checked distribution of labels in datasets and I create a list for expressing images for both datasets, moreover I see all the classes(labels) equally distributed. So I dont need to do Oversampling or Undersampling. 

### 4 - Data Preprocessing

For preparing datasets to the model I made data processing which is reshaping columns from (784) to (28,28,1), and for seperate vector I save label feature then process test and train data. After that I split train set into train and validation dataset. Validation set contains %30 of original train dataset and split will be 0.7/0.03. Later this process I controlled distribution of labels in train dataset and validation dataset.

<p align="center">
  <img width="750" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/number%20of%20items%20in%20each%20class%20in%20dataset.png">
</p>
<p align="center">
   <b>Number of Items in Each Class in Dataset</b>
</p>

<p align="center">
  <img width="750" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/number%20of%20items%20in%20each%20class%20in%20validation%20dataset.png">
</p>
<p align="center">
   <b>Number of Items in Each Class in Validation Dataset</b>
</p>

### 5 - Modelling 


### 6 - Result & Future Work

As a result, my model gives overally good results. 

<p align="center">
  <img width="750" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/accuracy.png">
</p>
<p align="center">
   <b>Accuracy of the Model</b>
</p>

<p align="center">
  <img width="750" height="500" src="https://github.com/HalukSumen/FashionMnist/blob/main/images/loss.png">
</p>
<p align="center">
   <b>Loss of the Model</b>
</p>





For better results, data augmentation can be implemented or data size can be expandable. 

