======== Problem Statement =======

Task 1: Predict the winner of the tournament

Task 2: Predict the top team in the points table after the completion of the league matches

Task 3: Predict the team with the highest points for successful raids.

Task 4: Predict the team with the highest points for successful tackles.

Task 5: Predict the team with the highest super-performance total.

Task 6: Predict the player with the highest SUCCESSFUL RAID percentage.

Task 7: Predict the player with the highest SUCCESSFUL TACKLE percentage.

======== Solution ===================

Step1: Scrap data from Prokabaddi website

Step2: Data was highly imbalanced so we use SMOTE(Synthetic minority over sampling) technique to balance the dataframe.

Step3: Here we use XGBoost to train and get high accuracy of our model 

Step4: Once model done we used that model to predict Season 7 to get Winner,Top team in points table,team with successful Raids,team with successful tackles,team with Super performance,Player with successful Raids percentage and Player with highest successful Tackle.


========Thank You======================
