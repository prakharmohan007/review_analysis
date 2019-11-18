# Analysis and rating prediction of reviews 

# Order of execution
Run all the cells in each notebook in the following order
1. Text_summary_generation.ipynb
2. Baseline.ipynb
3. CNN_data_processing.ipynb
4. CNN_text_review_and_generated_summary.ipynb 
5. CNN_text_review_modified_architecture.ipynb
6. review_classification.ipynb

Text_summary_generation.ipynb - code to generate summaries and it will generate csv file Reviews_summaries.csv that contain addition column named predicted_summary that will be used by CNN, RNN and baseline models.

Baseline.ipynb - code to train and test the Naive Bayes Classifier for predicting ratings.

CNN_data_processing.ipynb - preprocesses the data for CNN models training

CNN_text_review_and_generated_summary.ipynb - prediction of ratings using CNN based on text review, and generated summary

CNN_text_review_modified_architecture.ipynb - contains two models, first model will predict whether the given text review is positive or negative. Second model will predict the ratings based text review and the prediction of first model
