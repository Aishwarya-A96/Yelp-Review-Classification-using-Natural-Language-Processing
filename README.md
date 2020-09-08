Yelp-Review-Classification-using-Natural-Language-Processing

In Yelp Review classification I am going to  interpret whether review given  is a 5 star review or 1 star review using Natural Language Processing techniques by Naive Bayes Classifier.
Necessary libraries are imported and the dataset is loaded.
The dataset contains 10000 rows and 10 columns.
The length of the review is calculated and a new column named 'Length' is added.
The dataset does not contain any null values.
By doing visualisation it is found that 33% people gave 5 star rating and nearly 7.4% of users gave 1 star rating.
Numerical statistics is found using describe() 
Visualisation of how the users has given reviews based on length of the review provided is done by plotting a histogram on length of reviews for each star rating. 
Separating 1 star,3 star and 5 star reviews from the dataset and they are concatenated together.
Text cleaning techniques such as Punctuation Removal and Stopword Removal is done and applied to the concatenated version of 1 star, 3 star and 5 star reviews.
Comparing the original review with the cleaned version to see how the words are separated and listed in an array.
I Used CountVectorizer and converted the cleaned version of reviews  to zeros and ones.
I used Naive Bayes Classification Algorithm to classify the reviews and predict whether its 1 star, 3 star or its a 5 star review.
I gave the review and predicted whether it is a 1 star 2 star or 5 star review.
Then I splitted the dataset into training set and test test.
Training set contains 4437 rows and 31550 columns as words.
Test set contains 1110 rows and 31550 columns as words.
Naive bayes classification is used to fit the model and evaluation is done.
Confusion Matrix and Classification report is considered as evaluation metrics.
Accuracy was found to be 76%
Then only 1 star reviews and 5 star reviews are concatenated and text cleaning techniques are applied to the concatenated version of 1 star and 5 star reviews
Using CountVectorizer I converted the reviews into zeros and ones and fitted the model using Naive Bayes Classifier
By testing some sample reviews the model correctly interpreted as 1 star and 5 star review
Then the data set is splitted in training set and test test
Training set contains 3268 rows and 26639 columns
Test set contains 818 rows and 26639 columns
Naive bayes classification is used to fit the model and evaluation is done.
Confusion Matrix and Classification report is considered as evaluation metrics.
Accuracy was improved to 98%
