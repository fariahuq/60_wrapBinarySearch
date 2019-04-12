# 60_wrapBinarySearch

**What is meant by y=log2x?**
y=log2x means 2 raised to some exponent y is equal to x.

The graph of this has the y-axis as an asymptote. The curve starts from negative infinity, increases rapidly as x starts to increase, almost in a linear fashion, then slows down as x increases.


0. State the problem - Find the page in the phonebook that contains the target name.
1. State the recursive abstraction - When I am asked to find the page in the phonebook that contains the target name, the recursive abstraction can find the page that contains the target name in half of the pages in the phonebook.
2. Six parts of a generalized recursive solution
* Decision between base and recursion: If the lower limit is less than high limit.
* Solution(s) to base case(s): Return -1.
* Solution(s) to recursion case(s): 
* Invocation of the recursive abstraction: ```recursive( findMe, low, pageToCheck - 1); indexOf_recursive( findMe, pageToCheck + 1, hi);```
* leftover processing:
```
low
high
```
* combination:


