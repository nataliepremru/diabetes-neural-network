# Nueral Network for Diabetes Data

This project explores a dataset containing information on patients health in relation to diabetes, i.e columns include patients age, BMI, insulin levels and more. 

The porject begins with some exploratory data analysis through data visualisations such as bar charts, box plots and a correlation matrix to spot trends in the data and highlight inconsistancies.

It then preprocesses the data to ensure it is fit for modelling by replacing null values (in this case, zeros) with appropriate averages.

Finally, it builds an artificial neural network comprised of an input layer, two hidden layers, a regularisation layer and an output layer which gains an accuracy score of 75.94%.

While doing this project I found that using too many hidden layers or neurons lead to overfitting, so I made sure to keep the model simple enough so that the results were accurate.
