The project implements a machine learning pipeline for movie genre classification using textual data, particularly plot summaries. After importing required libraries, it loads and preprocesses datasets containing movie IDs, titles, genres, and descriptions. Visualization techniques like bar plots are employed to explore genre distribution and description lengths across different genres.

For model training, the data is vectorized using TF-IDF (Term Frequency-Inverse Document Frequency) transformation, which converts textual data into numerical representations. Three classifiers, namely LinearSVC, Logistic Regression, and Multinomial Naive Bayes, are trained on the TF-IDF transformed data. The dataset is split into training and validation sets, and the classifiers are evaluated using accuracy scores and classification reports.

Despite achieving a validation accuracy of approximately 58%, the model's performance drops significantly when evaluated on the test data, yielding only around 9% accuracy. This suggests potential overfitting or generalization issues that need to be addressed. Additionally, a function is provided to predict movie genres based on plot descriptions.

Overall, the project outlines a basic framework for movie genre classification using machine learning techniques, but further optimization and tuning are required to improve its performance and generalization capabilities.

Datasets Link:- https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb
