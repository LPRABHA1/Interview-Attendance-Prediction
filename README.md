# Interview-Attendance-Prediction
The Data is a csv from Kaggle. 
This has Recruiter's data for an Scheduled Interview. The Recruiter follows up with Candidates who had initially accepted to attend the interview. The Recruiter asks the Candidates 8 questions, to understand the psychology of the Candidate, if he is really interested and attend the interview or miss the interview. It is required for the Recruiter to arrive at a fair number, so that he can arrange the panel.

The aim of the project is to predict the Interview Attendance using Logistic Regression and Decision Tree Model.
Coding is in R program. Used Tidyverse, stringr, dplyr, data.table, boot, ISLR packages.
Based on the answers, scores are created so that the columns can be Binomial - '0' or '1' and "Yes" and "No".
These scores are used to predict the Attendance using the models.

