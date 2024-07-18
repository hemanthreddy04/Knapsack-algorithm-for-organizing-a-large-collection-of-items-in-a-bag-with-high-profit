# Knapsack-algorithm-for-organizing-a-large-collection-of-items-in-a-bag-with-high-profit

# 1. Problem Definition:
An optimization problem where the objective is to determine the optimal way of packing
luggage for traveling with a limited capacity to maximize the value of the items packed
inside .

# 2.Problem Explanation example:
Imagine going on a trip and having a backpack with limited space. You want to
pack as many items as possible, but you cannot exceed the weight capacity of the backpack.
You have a list of items with their weights and values, and you want to choose the items that
will maximize the total value while not exceeding the weight capacity of the backpack.

# 3.Design Techniques used:

# 1)Greedy approach

The basic idea of the greedy approach is to calculate the ratio profit/weight for each item
and sort the item based on this ratio. Then take the item with the highest ratio and add
as much as possible (can be the whole element or a fraction of it).
This will always give the maximum profit because, in each step it adds an element such that
this is the maximum possible profit for that much weight.

# 2)Dynamic Programming Approach

Since subproblems are evaluated again, this problem has Overlapping Sub-problems
property. So the 0/1 Knapsack problem has both properties of a dynamic programming
problem. Like other typical Dynamic Programming(DP) problems, re-computation of the
same subproblems can be avoided by constructing a temporary array K[][] in a bottom-up
manner.
