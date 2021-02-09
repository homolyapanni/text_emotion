# text_emotion
In my project, I work with emotion detection for which I use with data of tweets. First, I clean my data and do some pre-processing methods.  Besides my own features I use feature extraction also. My own features are the followings:
  1.	Number of the words in the record
  2.	Frequent words: where the function gives 1 if the word is in the instance,else it gives 0
  3.	POS-tag: where the function gives the number of the part of speech in the instance
In my code, I put my own features into one data frame. After I convert the data frame to sparse matrix and i concatenate with the feature extractions. This will be the feature set which I split 3 disjoint sets of different sizes ( traning-validation-test set). Training procedure is implemented by different machine learning algorithms like decision tree, random forest, logistic regression, Naive Bayes and SVM. 
