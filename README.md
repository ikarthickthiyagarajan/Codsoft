***Spam Classification with Naive Bayes and Support Vector Machines***
*Overview*
This project focuses on classifying spam and non-spam messages using two machine learning algorithms: Naive Bayes and Support Vector Machines (SVM). The dataset used for training and testing contains a collection of text messages labeled as spam or non-spam.

Getting Started
Dataset: The dataset used in this project is available in the spam.csv file. It contains two columns: v1 for the message label (spam or ham) and v2 for the message text.

Dependencies: Before running the code, ensure you have the necessary Python libraries installed. You can install them using pip:

Copy code:
pip install numpy pandas matplotlib scikit-learn
Code Execution: The main code is provided in the Python script spam_classification.py. You can run the script in your preferred Python environment.

Exploring the Dataset
The distribution of spam and non-spam messages is visualized using bar and pie charts.
The most frequent words in both spam and non-spam messages are analyzed and plotted.
Feature Engineering
Text data is transformed into numerical features using the CountVectorizer from scikit-learn.
Predictive Analysis
Multinomial Naive Bayes Classifier
A range of alpha values is tested for the Naive Bayes classifier.
Model performance metrics such as accuracy, recall, and precision are evaluated.
Support Vector Machine (SVM)
Different values of the regularization parameter (C) are tested for the SVM classifier.
Performance metrics are calculated and compared.
Results
The best performing models for both Naive Bayes and SVM classifiers are identified based on precision.
Confusion matrices are generated to visualize model performance.
Conclusion
In this project, we explored the task of spam classification using Naive Bayes and Support Vector Machines. Both classifiers achieved high accuracy in distinguishing between spam and non-spam messages. The code provided can be further extended or optimized for different datasets or classification tasks.
