The task is to make ML algorithm that will predict the cost of a second hand car depending on different info given about the car. 
To evaluate, the Percentage Mean Absolute Error(PMAE) will be used. 
The data given and all the data that will be requested is related to the Russian car market, so all the prices
are given in Russian currency(Russian Ruble), and some of the prices might be regional.

The main challenge of the task comes from the fact that the data for training the model must be collected 
seperately. Since the data from test.csv was collect from the website auto.ru, so the information for training the
model will be collected there as well. 

The file "Car Price Prediction" contains the code for predicting the price, while the file "Data Collection.ipynb" has the code for
parcing the data from auto.ru. The input block 2 of this file does not follow pep-8 standard, so it is hard to read as of now. 

Archive test.zip contains the testing data frame that is used for validation on Kaggle, it contains ifnformation about
34686 different cars.

Files train_X.csv contain the information from auto.ru that was used for training the model. More about that is written in 
"Process, results and outcomes.txt". 

The project was supposed to be done in a team of 2-3 people, yet was handled single-handedly with the excpetion of asking
some peopl to run the parcing code.

The best result achieved was 29.09 on Kaggle. More about that in "Process, results and outcomes.txt". 