# Model_selection_crossvalidation
Review accuracy estimation methods and compare methods:  crossvalidation and bootstrap

In this work sklearn built in dataset 'iris dataset' has been used train and test dataset. You can try your won dataset
For more details pleae visit my Kaggle page: 

# Steps
- import required libs and sklearn iris dataset
- create X and Y data set to train Y = wX + b model 

- Model selection: KNeighborsClassifier
- import cross validation model
- run model for range of K values for KNeighborsClassifier and find the best K value for the model
- Cross validation CV = 10 taken
- Model selection:LogisticRegression 
- import cross validation model
- Run model for different optimizer: ['newton-cg', 'lbfgs', 'liblinear', 'sag', 'saga']
- find best score
- Cross validation CV = 10 taken


#That way you can find the best value to tune model parameter. 
#We can put a list of models and run a loop to select best model with best parameters
