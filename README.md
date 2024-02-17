# High-value-soccer-players
-	Background: On Jupiter notebooks I used pandas library to read and manipulate an online soccer data set and to plot soccer players by their wage and value 
-	First thing I want to do is get a feel for the data table I will be working with, so I pull up the stats per column and the first 5 entries of the table 
-	Next I want to clean the data. I will be looking for players who are a good deal so have high value and low current wage. So, I only want to select the player name, wage and value and have a fourth column of the difference between vale and the wage and sort based on that. I cannot just take the difference between value and wage as they are both string data types and are abbreviated with M or K. I must correct for this. 
-	I made a new function that extends the abbreviated numbers and turns them into float data types and using the replace method and regular expression I can remove the currency symbol so I am left with just a number. Now I can take the difference between wage and value and put the results in a column called difference. Finally I will filter out any platers with a negative value and sort by difference column descending. 
-	Next, using Seaborn(A python library built to simplify matplotlib)  I can plot the players and make a nice visualization
-	I can make a better visualization using the Bokeh library that uses a hover tool. 
