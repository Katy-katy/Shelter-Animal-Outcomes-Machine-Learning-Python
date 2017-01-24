# Shelter Animal Outcomes using python, ipython notebook, pandas, seaborn, sklearn, matplotlib


This project was written for a Kaggle competition: https://www.kaggle.com/c/shelter-animal-outcomes/data 
My goal was to predict the outcome of the animals as they leave the Animal Center.
I used the date comes from Austin Animal Center (October 1st, 2013 - March, 2016). 
Outcomes represenedt the status of animals as they leave the Animal Center.

I used multi class logistic regression for this project and got log_loss 0.92871. Then I slightly improve the result using VotingClassifier with logistic regression, random forest, and CalibratedClassifier as estimators. I got log_loss 0.92197.
 
I also did some useful observations.
Neutered Males and Spayed Females have a great chance to be adopted, but it is very hard to find a new family for Intact Males and Intact Femalse.
It is important for an animal to have an ID tag (I think that the shelter staff learned the names from the tags. The animals with unknown names have almost no chance to return to owners and have less chance to be adopted.
 

Please, see shelter.ipynb and Shelter_Animals_presentation.pptx for more information
