# Fake-job-detection-using-Sentiment analysis
Creating a model to classify a job posting as true and safe or not based on Sentiment Analysis.
Creating a word cloud visualization to identify the most common words among fake job postings.

Implemented a robust sentiment analysis model that leverages TFID features and adopts an ensemble approach. The ensemble combines the strengths of XGBoost and Random Forest classifiers through a Voting Classifier. Initially, I trained the model using labeled data from Kaggle. Fine-tuning involved adjusting the threshold to optimize the F1 score.

The model was then applied to label newly gathered data from web scraping. To further enhance performance, I retrained the model using both the initially employed labeled dataset and the newly labeled scraped data. This refined model underwent evaluation on an existing test group dataset, with a primary focus on identifying the optimal F1 score through threshold tuning.

The attached findings provide a detailed account of the outcomes for the final test set data, showcasing the success of the ensemble method in sentiment analysis.
