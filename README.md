The code is equal for problem 1 and problem 2, the only difference for the two is the number of iterations they make to keep the time between 15 and 20 seconds. 
After creating and defining all the variables I defined the evaluating function that controls if the current solution is valid using the check_solution function and if that is the case calculate the total values inside the knapsacks and print it if it is the best one.
Every iteration remove an item from the knapsacks that have gone past their capacity and add one random item to every other knapsack.

For the 3rd problem I faced the problem that if i initialize a random solution from the start the problem does not converge. This is propably a problem caused from the fact that we have too much knapsacks and too much items so a knapsack can be filled with too many items and it will be required too much iterations to emptying it. The solution 3 given that start from an empty solution and make the same iterations as the first two problems.

From my PC that is a Macbook Pro M1 the first 2 problems run the code in 15-20 seconds, the third one in about 3 minutes. The more iterations the better results, the only problem is that with a lot of knapsacks and items the problem explode in terms of time.
