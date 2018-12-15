# Defining Problem/Solution recursively

### Repeating Sub-problem
Choosing max between two int datatypes.  This same operation can be used in two cases:
1. Comparing between elements of the int array
2. Comparing the total for Aaron and the total for Lee

### Properties of the Larger Problem
* Alex is always first; Lee is always second. This implies turns can be based off of a modulo of 2
* Because of Java, arrays are immutable.  Elements can't be popped off.  Either use ArrayList or pointers.

# Plan for Memo-ization
*Memos are used to help number of times the sub-problem is repeated*, so my plan is:
