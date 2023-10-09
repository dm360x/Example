# Example code - works on PC only not MAC)
This R code conducts the following steps
1.  Installs the required packages.
2.  Activates the required libraries.
3.  Clears any existing vars.
4.  Loads and displays a correlation table (corr.csv) from the working directory with missing correlations.  Extracts the column names of the correlations.
5.  Determines where the missing values are in the correlation table.
6.  Imputes correlation values (using random values) between a user defined range (default 0.1 to 0.4) and creates a user defined number of variations of the original correlation table (as matrices).
7.  Note the above uses parallel processing leaving 1x core active to run MS Windows etc.
8.  Displays an example correlation plot of the first variation using the names of the correlated variables from the .csv file.
9.  Displays 6x histograms of the values imputed of the missing correlations.
