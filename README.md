# Example code - works on PC only not MAC)
This r code conducts the following steps
1.  Installs the required packages (apologies if there are some excess packages, however, this code is an excerpt from a larger piece of code)
2.  Activate sthe required libraries
3.  clears any existing vars
4.  loads and displays a corrrelation table fromt he working directory with missing correlations
5.  determines where the missing values are in the correlation table
6.  Imputates correlation vaues between a user defined range (default 0.1 to 0.4) and creates a user defined number of variations of the original correltion table (as matrices)
7.  Note the above uses parallel processing leaving 1x core active to run windows etc
8.  Displays an example correlation plot of the first variation
9.  Displays 6x histograms of the values imputed of the missing correlations.
