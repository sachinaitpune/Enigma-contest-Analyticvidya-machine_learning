problem statement--

Data of quora question and answer is given with various coloums.

coloumns are-
ID
Sex
Age
Tags
Answers
Upvotes
Username

We have to predict the upvotes of random user from the test dataset.



##Approach

I have used Matplot library,seaborn for the data visualisation.Prepossessing was necessary because of some data i found was irrelevent and for that i have used MINMAX scalar,Binarizar after that I used Extratreeregressor over normal regressor to increse the score and to decrease the RMSE.
Feature engineering is very important in this approach like the colums having the 'SEX' should be coverted into binary form.
