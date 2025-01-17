%%writefile README.md
# Sentiment Classification Project

## Project Description
This project implements logistic regression with one-hot encoding to classify the sentiment of Amazon product reviews.

## How to Run
1. Clone the repository: https://github.com/ydeng9950/LELA60331-Coursework
2. Run the first cell to download the raw dataset.
3. Run the second cell to load the necessary libraries.
4. Run the third cell to organize the data for preprocessing.
5. Run the fourth cell to tokenize the reviews, identify the 10000 most frequent words and create the vocabulary for one-hot encoding.
6. Run the fifth cell to create the one-hot encoded matrix.
7. Run the sixth cell to split the data into test and training set.
8. Run the seventh cell to train the logistic regression classifier on training data.
9. Run the eighth cell to make predictions on the test data.
10. Run the ninth cell to calculate the accuracy of the model.
11. Run the tenth cell to calculate the precision, recall and F1-score of the model on the test data.
12. Run the eleventh cell to calculate the precision, recall and F1-score of the model on the training data.

## References
The dataset used in this project was provided by Dr.Colin Bannard and can be accessed here: (https://colab.research.google.com/github/cbannard/lela60331_24-25/blob/main/coursework/coursework_data_import.ipynb).
