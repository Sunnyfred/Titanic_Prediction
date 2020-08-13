# Titanic_Prediction

This is a Kaggle competition for Data science novice. 


Version_2:

	"Titanic_main_code_v2.ipynb" is the first successful version for predicting the Titanic Disaster(https://www.kaggle.com/c/titanic).
	Basic random forest model is implemented to give a public score of .77990.


	Libraries employed:

	numpy
	pandas
	matplotlib
	sklearn

Version_3:

	Do feature engineering based on version_2, remove feature "Embarked", the updated public score is .78229.


	Libraries employed:

	numpy
	pandas
	matplotlib
	sklearn
	seaborn
Version_4:

	Combined train set and test set, do further feature engineering, all features are not removed for this time. Use basic RF 
	after performing feature selection. There is no advance found in the result, the updated public score is .7511. Let's play
	with the model in the next version.


	Libraries employed:

	numpy
	pandas
	matplotlib
	sklearn
	seaborn	
	
Version_5:

	Based on the feature engineering of version 4, tuning hyperparameters using grid search. 
	Public score reach to 0.78468.


	Libraries employed:

	numpy
	pandas
	matplotlib
	sklearn
	seaborn	
	
Version_6:

	Futher feature engineering, tuning hyperparameters using grid search, ensemble voting method. 
	Public score reach to 0.76794.
	
Version_7:

	Based on version_5, optimizing random forest model.
	Public score reach to 0.79186.
	
