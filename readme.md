Data Preprocessing steps 

Label encoded the following columns
catCols = ['job','marital','education','default','housing','loan','contact','poutcome']

Used Minmax Scaler for continues Variables
numCols = ['balance','duration','pdays']

Binned Age Group in 5 Categories
bins = [17,25,35,50,60,90]
Basically 
17-25 Group 1
25-35 Group 2 
and so on 

This is called data smoothening
