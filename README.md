# Titanic-Learning-from-a-Disaster

# KAGGLE-Titanic---Machine-Learning-from-Disaster

My model was applied to the Kaggle competition: Titanic - Machine Learning from Disaster. [Competition page](https://www.kaggle.com/competitions/titanic/overview)

Kaggle is a Data Science site with competitions for those who want to learn (my case here) or compete. This is my first attempt at a Kaggle competition, and I really enjoyed the process



# TL: DR
[Notebook](https://github.com/Rofel/Titanic-Learning-from-a-Disaster/blob/main/Survival%20Prediction_Titanic%20-%20Machine%20Learning%20from%20Disaster.ipynb)
- Used method: Logistic Regression (stats model library).
- In this project, I used AI (chatGPT) to create plot codes as I was kinda unfamiliar with that and was a great tool to speed up the process.
- The notebook is commented to explain all the thinking processes and decision-making.
- Data Pre-processing and Data Visualization
- Creation of a new feature 'Child'
- Selecting features from Data Analysis and relation with the target data: 'Survived'
- Creating the model and checking for p-values and overall model accuracy (~81%)
- Pre-process of test data and prediction of results
- As a Learning Tool, took advantage of the fact the Kaggle site gives a score by the time of submission and we can submit 10 results per day, in this competition, to create two subsets of results, varying thresholds for it.
- Exported the results and check scores granted.

# Results

- 77,88% was the best score, using the normal threshold (0.5), and having the highest overall model accuracy (81%) at train data.
- From this, will start getting familiarized with other methods for Binary prediction, such as Random Forest, Support Vector Machines (SVM), Naive Bayes, etc.
- Tried Clustering with K-Means, but became hard to visualize the relations with the target, so preferred to use Logistic Regression.
