# StuCred-Cred.it

The code *generates a synthetic dataset* of student financial and academic data, then *trains a deep learning model* to predict whether a student will repay a loan. 

1. *Data Generation*: Creates 1,000 student records with features like CGPA, spending habits, and financial stability, using latent factors to simulate realistic correlations. A loan_paid_back label is assigned based on a heuristic formula.
   
2. *Model Training*: A neural network is trained on this dataset to classify students as likely or unlikely to repay loans. The model uses multiple hidden layers with batch normalization and dropout for better generalization.

3. *Prediction*: After training, the model evaluates test data and predicts loan repayment probabilities for students.
