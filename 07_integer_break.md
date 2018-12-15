# Defining Problem/Solution recursively

### Repeating Sub-problem
seeing if a number can be evenly split by i, where i is incremented

### Properties of the Larger Problem
* The maximum product happens by increasing the operands

# Plan for Memo-ization
*Memos are used to help number of times the sub-problem is repeated*, so my plan is:

My plan is to create an n-ary tree where every node is an operand and every level
of the tree can be multiplied to get a product.  A node will have children if the
value of the node is modulo'd by j and the result is 0, the node will have j
children
