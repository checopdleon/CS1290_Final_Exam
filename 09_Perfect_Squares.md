# Defining Problem/Solution recursively

### Repeating Sub-problem
Subtracting an already known perfect square number from the current number, where
the perfect square number is less than or equal to the current number.

### Properties of the Larger Problem
It's like a prime factorization algorithm by the famous Greek mathematician.

# Plan for Memo-ization
*Memos are used to help number of times the sub-problem is repeated*, so my plan is:

Given an n, integer, paassed in I build up an array of perfect squares until the
perfect squares are equal or less than the n int. I subtract the perfect square
from the current number and then recursively do this operation until the difference is
either 0 or 1. The trick is to first look up to see if the max square number in the array
is larger than the current number, because then I can quickly point to it and to the 
preceding numbers rather than building up the array every time.
