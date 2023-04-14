# Cardio-Vascular-Diseases

Goal:-
To learn the historical data from cardio.csv file and predict the output that the person is a part of cardiac arrest or not.

Objective:-
1.To establish the relationship between dependent and independent variable.
2.To predict the new observation.

Tols that are Used:-
The project is performed on Jupyter notebook,in that we use seaborn libraries for visualisation of data. As well as numpy,pandas,sklearn,matplotlib,pickle and flask etc are used for completion of my task.

Working:-
   Firstly we done cleaning on given dataset then visualising of data by using matplotlib and seaborn. After visualisation it seems that data is not in proper scalling so we done scalling, to put data into  same unit.Then we split data into training and testing part.
    After all we build different models on it like Logistic Regression,KNeighbours,Decision Tree,Random Forest,Bagging,Boosting and Voting classifier on it. From all models xg Boost gives us a best accuracy i-e 74% so we done HPT on it.We done RandomisedSearchCV in that we give different parameter like n estimator,max_depth and learning_rate.
    RandomizedSearchCV gives us accuracy that is 73% so we take predictive results on xg Boost model.At the end Web application is linked to Python and html through Flask and Deployment of model is done.

Conclusion:-
Application gives us the predictive result whether person will be the part of cardiac arrest or not.
