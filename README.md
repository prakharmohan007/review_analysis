# Analysis and rating prediction of reviews 

Download the data from this link: https://www.kaggle.com/snap/amazon-fine-food-reviews

# Order of execution
Run all the cells in each notebook in the following order
1. Text_summary_generation.ipynb
2. Baseline.ipynb
3. CNN_data_processing.ipynb
4. CNN_text_review_and_generated_summary.ipynb 
5. CNN_text_review_modified_architecture.ipynb
6. review_classification.ipynb

# File descriptions
Text_summary_generation.ipynb - code to generate summaries, it will generate csv file Reviews_summaries.csv that contain addition column named predicted_summary which will be used by CNN, RNN and baseline models.

Baseline.ipynb - code to train and test the Naive Bayes Classifier for predicting ratings.

CNN_data_processing.ipynb - preprocesses the data for CNN models

CNN_text_review_and_generated_summary.ipynb - prediction of ratings using CNN based on text review, and generated summary

CNN_text_review_modified_architecture.ipynb - contains two models, first model will predict whether the given text review is positive or negative. Second model will predict the ratings based text review and the prediction of the first model

review_classification.ipynb - contains models for review classification and rating prediction. Part 1: A model to classify reviews into positive and negative. Part 2: A model to predict the rating of reviews on a scale of 1 to 5. The variable "text_type", specified in the first line of Part 2, specifies the use of full text review (text_type = 1) or review summary (text_type = 2).
