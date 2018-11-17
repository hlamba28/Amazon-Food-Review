In this case study, I have solved a Text Classification problem using different Machine Learning Techniques.
Dataset link => https://www.kaggle.com/snap/amazon-fine-food-reviews

Folder Descrptions:

1. Exploratory Analysis and Cleaning:
This contains a Jupyter Notebook wherein I perform the tasks like reading data, exploratory data analysis, data cleaning, etc.
This file creates two pickle files namely "final.sqlite" and "list_of_sent_for_input_to_w2v.pkl" which are used in the susequent folders, hence must be saved on your hard disk.

2. KNN:
In this folder I use K-Nearest Neighbors classifiers to classify the food reviews using 3 different featurizations namely "Bag of Words", "TFIDF" and "Word to vec", hence I have 3 different Jupyter Notebooks.

3. Naive Bayes:
In this folder, I apply Naive Bayes algorithm using Bag of Words featurization of the text; with and without Upsampling of the dataset, hence the two Notebooks.

4. Logistic Regression:
In this folder I apply Logistic Regression using Bag of Words and Word to Vec featuerization of the text.
Through different featurizations (Bag of Words, Word to Vec 100 dimensions, Word to Vec 200 dimensions), it can be concluded that Linear models tend to perform well if the dimensionality of the data is high.
