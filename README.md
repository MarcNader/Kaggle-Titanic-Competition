# Kaggle-Titanic-Competition
This repository holds my submitted code for Kaggle's competition "Titanic - Machine Learning from Disaster"

About: 
Shortly, the challenge was to create a machine learning based model that will be able to predict which passengers survived the Titanic Shipwreck.

My model managed to predict the Survival status of the 418 passengers specified with an accuracy of 0.75358% when I used DecisionTreeClassifier model because it was the model that had the highest precision percentage from the 3 models I was comparing with. 

However when I then resubmitted with LogisticRegression model it gave higher accuracy of precisely 76.55%. Even though that when I was evalutating my model it had a precision percentage of only 72%. 

With some basic analysis I deduced that this probably happened due to that I was only using 80% of train data to train my model and also only testing on a small data which was 20% of the actual train data. But on the other side the given test data was much bigger than my 20% test sample and also I got to use my whole trainning data
So this could probably explain the reason behind the final result I got from each model.

Link to competetion with all the details: https://www.kaggle.com/c/titanic


