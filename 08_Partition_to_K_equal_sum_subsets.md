# Defining Problem/Solution recursively

### Repeating Sub-problem
I keep having to check whether if I have this int
already.

### Properties of the Larger Problem
My friend explained it like this: I'm a thief and I'm limited to a 
weight I can carry. I can exhaustively decide to steal something 
based the item's weight or value. I need to maximize the total amount
of value i can steal with the lightest total weight.

# Plan for Memo-ization
*Memos are used to help number of times the sub-problem is repeated*, so my plan is:

I have to keep track of items, or ints in this case, that I have already
considered to be taken.  Instead of weight and value, in this problem I'm considering
the sum versus including another int.
