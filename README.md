# Stackoverflowtagpredictor
I have predicted the tags for more than half a million questions of stackoverflow using EDA ,NLP tools and logistic regression

Detail of the case study is:-

Problem Description
Suggest the tags based on the content that was there in the question posted on Stackoverflow.

Data Overview
Source of Data : https://www.kaggle.com/c/facebook-recruiting-iii-keyword-extraction/

All of the data is in 2 files: Train and Test. Train.csv contains 4 columns: Id,Title,Body,Tags. Test.csv contains the same columns but without the Tags, which you are to predict. Size of Train.csv - 6.75GB Size of Test.csv - 2GB Number of rows in Train.csv = 6034195

Dataset contains 6,034,195 rows. The columns in the table are: Id - Unique identifier for each question Title - The question's title Body - The body of the question Tags - The tags associated with the question in a space-seperated format (all lowercase, should not contain tabs '\t' or ampersands '&')



