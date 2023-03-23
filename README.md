# Spam-Classifier

The Naive Bayes algorithm is a classification algorithm based on Bayes' theorem. It is a probabilistic algorithm that predicts the class of an input by computing the conditional probability of the input given each possible class, and selecting the class with the highest probability.

The dataset contains two columns, one with the text of the messages, and one with the corresponding label (spam or ham).

Textprocessing the messages that includes lowering cases, remove stopwords, punctuation, creating lemmas for all words.

Insigts of EDA includes finding imbalance in the data class of spam(minority) and ham. SmoTe is used to treat this. 

Here's how the SMOTE algorithm works:

    For each instance in the minority class, find its k nearest neighbors (k is a user-specified parameter).

    Randomly select one of the k nearest neighbors and create a synthetic instance by interpolating between the features of the selected instance and the original instance.

    Repeat steps 1 and 2 until the desired level of minority class oversampling is achieved.

Prediction: For each input in the testing set, the Naive Bayes algorithm calculates the conditional probability of the input given each possible class, using the trained probability distributions.

The algorithm then selects the class with the highest probability as the predicted class for that input.

Evaluation: The performance of the Naive Bayes algorithm is evaluated by comparing the predicted classes to the actual classes in the testing set, and computing metrics such as accuracy, precision, recall, and F1 score.
 

