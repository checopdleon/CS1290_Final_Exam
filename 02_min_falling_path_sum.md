# Defining Problem/Solution recursively

### Repeating Sub-problem
Finding the next i, j indices to move to

### Properties of the Larger Problem
* It's like a pre-fix tree problem
* Return an array of arrays, call it answer array

# Plan for Memo-ization
*Memos are used to help number of times the sub-problem is repeated*, so my plan is:

Have a helper method where I would not only pass the array but also pass in the answer 
array and be building the answer array as I go. The point is to store values of visited
indices for every path. When you move to a new index calculate the previous i, j 
coordinate, look for that value in the answer array then fill in the new value in the 
appropriate spot of that path.
