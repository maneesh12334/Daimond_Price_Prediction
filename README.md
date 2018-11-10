# Daimond_Price_Prediction
## Problem 
A diamond distributor has recently decided to exit the market and has put up a set of 3,000 diamonds up for auction. Seeing this as a great opportunity to expand its inventory, a jewelry company has shown interest in making a bid. To decide how much to bid, the company’s analytics team used a large database of diamond prices to build a linear regression model to predict the price of a diamond based on its attributes. I, as the business analysts, are tasked to apply that model to make a recommendation for how much the company should bid for the entire set of 3,000 diamonds.

#### Step 1 – Understand the data: There are two datasets.
#### diamonds.csv contains the data used to build the regression model.
#### new_diamonds.csv contains the data for the diamonds the company would like to purchase.
Both datasets contain carat, cut, and clarity data for each diamond. Only the diamonds.csv dataset has prices. We'll be predicting prices for the new_diamonds.csv dataset.

Carat represents the weight of the diamond, and is a numerical variable.
Cut represents the quality of the cut of the diamond, and falls into 5 categories: fair, good, very good, ideal, and premium. Each of these categories are represented by a number, 1-5, in the Cut_Ord variable.
Clarity represents the internal purity of the diamond, and falls into 8 categories: I1, SI2, SI1, VS1, VS2, VVS2, VVS1, and IF. Each of these categories are represented by a number, 1-8, in the Clarity_Ord variable.

#### Step 2 – Calculate the predicted price for diamond: 
For each diamond, plug in the values for each of the variables into the linear model (equation). Then solve the equation to get the estimated, or predicted, diamond price.
