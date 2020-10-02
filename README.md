Business Optimization (Knapsack Problem)

The knapsack problem offers a very simple question: If Indiana Jones' satchel can only carry C lbs of treasure and each treasure, i, has a weight of Wi and a monetary value of Vi, which items should Indy put into his bag to maximize profit while minimizing the weight of his satchel? 

However, there is a small twist: You do not know the maximum weight, C, Indy can carry until you have selected which items you want to put into his satchel. And if you happen to exceed C, you cannot keep any of the treasure. 

In this case, C is a uniform random variable between 500 and 1000.

For this problem, I used Monte Carlo simulation to not only determine the probability that my list of items will stay under the random weight limit C, but also which combination of items are worth the risk for the extra value.

In the file Knapsack_Input.csv, there are 3 different instances of treasure to choose from. The first row of each instance contains the weight of each treasure item and the second row contains the value of said treasure item. 
