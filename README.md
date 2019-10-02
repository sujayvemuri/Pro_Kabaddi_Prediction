======== Problem Statement =======

Task 1: Predict the winner of the tournament

Task 2: Predict the top team in the points table after the completion of the league matches

Task 3: Predict the team with the highest points for successful raids.

Task 4: Predict the team with the highest points for successful tackles.

Task 5: Predict the team with the highest super-performance total.

Task 6: Predict the player with the highest SUCCESSFUL RAID percentage.

Task 7: Predict the player with the highest SUCCESSFUL TACKLE percentage.

======== Solution ===================

Step1: Scrap the data from Prokabaddi website

Step2: Data was highly imbalanced. So we used SMOTE(Synthetic Minority Over Sampling) technique to balance the dataframe.

Step3: Here we used XGBoost to train and get high accuracy of our model.

Step4: Once the model is trained, we used that model to predict the Season 7 to get the Winner,Top team in the points table, team with successful Raids, team with successful tackles, team with Super performance, Player with successful Raids percentage and Player with highest successful Tackle.

========Thank You======================
