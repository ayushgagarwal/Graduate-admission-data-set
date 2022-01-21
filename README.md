# Graduate-admission-data-set

Task - Using the predicting variables - GRE score, TOEFL score, University Rating, etc - see if you can predict the likelihood of admission of a new candidate.

Data set - https://www.kaggle.com/mohansacharya/graduate-admissions

Most of the data cleaning checks on the data were done directly through excel. It wasn't a huge challenge as the data set wasn't that big. I just had to change the column name of Serial No. , LOR and Chance of Admit. Also, I made sure that Seriol No had been numbered correctly from 1 to 500.

I took a non traditional way of analysing the data - I did it using Tableau.

Among other things, one of my major findings when I analysed the data was the multicollinearity problem between GRE, TOEFL, CGPA.

I tried out various algorithms and found out that Multiple Linear Regression worked the best with the data with it's MSE being the lowest (0.05)
