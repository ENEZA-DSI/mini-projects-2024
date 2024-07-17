# Impact of Data Preprocessing on Machine Learning from a Diabetes Dataset

A diabetes dataset, known as the Pima Indians Diabetes Dataset, is available from https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database. This dataset can be used to train a binary classifier to predict the outcome (0 or 1), which stands for whether a patient has diabetes or not. You will notice that this dataset has a lot of missing values, which appear as zeros where zeros do not make sense. In addition, some features have a much wider range than others, which can pose a challenge for machine learning. It is normal for real-world data to have such imperfections, and it is the job of the data scientist to mitigate them.

This project requires you to carry out data preprocessing activities and then train models on the new version of the dataset. Take note of any improvement in model performance resulting from the preprocessing activities.

## Project Objectives:
1. Demonstrate how to impute missing values.
2. Demonstrate how to normalize or standardize data.
3. Use k-fold cross-validation to evaluate different machine learning algorithms on the preprocessed dataset. (Do not use deep learning as this dataset is too small for that.)
