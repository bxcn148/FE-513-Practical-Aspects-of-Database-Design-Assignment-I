Download link :https://programming.engineering/product/fe-513-practical-aspects-of-database-design-assignment-i/


# FE-513-Practical-Aspects-of-Database-Design-Assignment-I
FE 513 Practical Aspects of Database Design Assignment I
Before starting this assignment, please go through the ’Google’s R coding style guide’ (available under Week 2 module on Canvas). Please submit R code as well as a pdf report le, containing results and the corresponding R code. Rmarkdown is highly recommended for generating the report. More guideline on using Rmarkdown please see help documentation under week 3 module.

Part I

1.1 Vector

Create 2 vector, each containing 10 random numbers.

Append the second vector to the rst one.

Calculate the mean of the new combined vector.

For each number in the new combined vector, if it is lager than the mean then print out a ’True’, otherwise print out a ’False’.

1.2 Matrix

Create a vector with 100 random numbers.

Transfer the above vector into a 10 by 10 matrix M.

Find the transposed matrix MT . Print the value of element who is in the second row and the rst column of MT .

Write a nested loop to calculate the inner product between MT and M. The result is also a matrix N = hMT ; Mi.

Calculate the same inner product using operator % %. And compare two results.

1.3 Function

Load the given CSV le in R

Delete the columns containing NA(empty values).


Calculate daily log return for each stock. (Hint. log return is de ned as


rt = ln

Pt

= ln (Pt) ln (Pt 1), where Pt is the stock price at time t.)

Pt 1

Calculate the mean and standard deviation of log return for each stock. Transfer the result into a 2 by N data frame (N is the number of stocks). (Hint. Function ’apply’ is a better choice than ’for loop’.)

Build a graph with two sub-plots. In the rst sub-plot, plot the rst three stocks’ daily prices. The y axis is stock price and x axis is date. In the second sub-plot, build a scatter plot of the statistical result you calculated above. In other words, the x-axis is the stocks’ names and the y-axis is the statistical values. (Notes. Please include legend, tile, and axis labels for each sub-plots.)

Bonus (10 pt)

Do problems in section 1.3 again using ’pipe’.

Part II

Try to use package ‘quantmod’ to download data, and search functions in ‘quant-mod’ package to do following tasks.

Download Amazon daily stock price data from 2021-01-01 to 2021-12-31. And save the data to a csv le.

Calculate weekly log returns based on adjusted close price.

Calculate median, mean, standard deviation of log returns.

Plot the distribution of stock daily log returns (Hints. Histogram is a good choice to show the distribution. Controlling the number of bins in histogram can achieve a good resolution).

Count how many observation in this series whose log return is between 0.01 and 0.015.
