# Coin-Problem
Just for fun project

A code for pulling statistics for the following math problem:

You have a box with N coins inside of it. The coins are numbered from 1 to N. You play a game; for every iteration of the game, 
you pull coins out of the box randomly until it's empty. For every iteration, you make a total amount of money equal to: 
the value of the first coin extracted, plus the absolute value of the difference between each subsequent coin extraction
and the one previous to it.
Example: N=4 and the following is the drawing order: 3, 1, 4, 2 ==> Total Money Made = 3 + |3-1| + |1-4| + |4-2| = 10

Two notebooks are included. One uses the permutation function of itertools library to deteremine all possible combinations and then calculate the desired statistics. Also, for this, two ways of calculating; a forward and a recursive method, are implemented. The second one uses the random library to generate random integers. Purpose of the second notebook is to be able to randomnly generate combinations and see the results as we go. This is particularlu useful when N is large and you cannot test all combinations but want to get a close enough statistic.
