The file restaurant-rating-prediction.ipynb has the code used for predicting the rating of a restaurant, after which it saves it into
submission.csv.
The file mock.ipynb was used as a draft, does not follow pep-8 standart and has certain differences in the code.


The datasets contains information about restaurants. This infomation needs to be used to build a regression model capable of predicting the rating of a restaurant. 
First data frame, df_train(main_task.csv) contains information about 40000 restaurants and will be used for training and validating the model.
The df_test('kaggle_task.csv) has information about 10000 restaurants, which rating needs to be predicted.
Following information can be found in the data frames:
1. Restaurant_id - restaurant identification number;
2. City - city in which restaurant is located;
3. Cuisine Style - tags for food that is served in the restaurant;
4. Ranking - rank of a restaurant compared to the other restaurants in the city;
5. Rating -  restaurant rating according to TripAdvisor, dependant variable and the value that needs to be predicted(1 to 5);
6. Price Range - range of prices in a restaurant(category);
7. Number of Reviews — Number of Reviews;
8. Reviews - two reviews displayed on the website and their respective dates;
9. URL_TA — URL on TripAdvisor;
10. ID_TA — Identificator of restaurant in TripAdvisor's DataBase.

