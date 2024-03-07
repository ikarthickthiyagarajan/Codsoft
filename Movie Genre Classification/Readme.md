Movie Genre Classification Project
This project aims to classify movie genres based on their descriptions using Natural Language Processing (NLP) techniques and a Multinomial Naive Bayes classifier.

Overview
The project consists of several key components:

Data Retrieval and Preprocessing: The IMDb genre classification dataset is downloaded and preprocessed to prepare it for model training.

Exploratory Data Analysis (EDA): Visualization of the distribution of genres in the training data is performed to gain insights into the dataset.

Text Cleaning: The movie descriptions are cleaned by removing special characters, punctuation, stopwords, and performing stemming.

Text Vectorization: TF-IDF vectorization is applied to convert the text data into numerical features suitable for machine learning models.

Model Training: A Multinomial Naive Bayes classifier is trained on the TF-IDF transformed data to predict movie genres.

Model Evaluation: The performance of the trained model is evaluated using accuracy and classification report metrics on the validation set.

Predictions: Finally, the trained model is used to make predictions on the test data, and the results are saved to a CSV file.

Usage
To use this project, follow these steps:

Install Dependencies: Make sure you have all the necessary dependencies installed. You can install them using pip:

Copy code
pip install pandas matplotlib seaborn nltk scikit-learn
Run the Notebook: Execute the provided Jupyter Notebook or Python script. Make sure to adjust file paths if necessary.

Review Results: After running the code, review the generated visualizations, model performance metrics, and predicted genres.

Customization: Feel free to customize the code according to your needs, such as trying different preprocessing techniques or experimenting with other machine learning algorithms.

Files Included
Genre_Classification_Project.ipynb: Jupyter Notebook containing the project code.
predicted_genres.csv: CSV file containing the test data with predicted genres.
