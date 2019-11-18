# Analysis and rating prediction of reviews 

# Order of execution
1. Text_summary_generation.ipynb , Generates 'Reviews_summaries.csv' file which will be used by the following files
2. Baseline.ipynb, runs the baseline models
3. CNN_data_processing.ipynb, Preprocesses the data for CNN models training
4. CNN_text_review_modified_architecture.ipynb, Generates the CNN models for reviews
5. CNN_text_review_and_generated_summary.ipynb, Generates the CNN models for review summary
6. review_classification.ipynb


File Baseline.ipynb has the code used to train and test the Naive Bayes Classifier for predicting ratings.

File Text_summary_generation.ipynb has the code to generate summaries and it will generate csv file Reviews_summaries.csv that contain addition column named predicted_summary that will be used by CNN, RNN and baseline models.
