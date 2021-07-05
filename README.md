# Titanic-Survival-Likelihood
In this project, we have data of 800+ passengers on the fateful Titanic ship that sunk in 1910. The goal of this project is to use this data with passenger’s social attributes as predictors/variables to build a logistic model to predict whether a passenger survived the tragic accident.  

Using stepwise regression from base R, based on AIC and deviance values the best model we get for prediction is  
Survived ~ Sex + Age + TicketFare+ FirstClass + SecondClass + 
    FamilySize + Mr + Master + Southampton 
 
Variable dictionary and the model are discussed in detail in the main report. Out of the given 14 predictors we observe that only 9 variables are required to give the best model in terms of prediction. The performance metrics we get from the above model is shown below. 



                  	  AUC>0.7? 	Cost(AMR) 
In-Sample Testing 	  Yes(0.872) 	50.08%
Out-of-Sample Testing Yes(0.869) 	49.63
 
 


                           Table 2: Model Performance Evaluation (in-sample and out-of sampl
