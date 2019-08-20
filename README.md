# Recursion-Problems

Problem 1:  This interview question requires you to reverse a string using recursion. Make sure to think of the base case here.
Again, make sure you use recursion to accomplish this. Do not slice (e.g. string[::-1]) or use iteration, there must be a recursive call for the function.

Problem 2:  Given a string, write a function that uses recursion to output a list of all the possible permutations of that string.
For example, given s='abc' the function should return ['abc', 'acb', 'bac', 'bca', 'cab', 'cba'].
Note: If a character is repeated, treat each occurence as distinct, for example an input of 'xxx' would return a list with 6 "versions" of 'xxx'.

Problem 3:  Implement a Fibonnaci Sequence in three different ways:
  (1) Recursively
  (2) Dynamically (Using Memoization to store results)
  (3) Iteratively

Problem 4:  Given a target amount n and a list (array) of distinct coin values, what's the fewest coins needed to make the change amount.
For example:
If n = 10 and coins = [1,5,10]. Then there are 4 possible ways to make change:
  (1) 1+1+1+1+1+1+1+1+1+1
  (2)	5 + 1+1+1+1+1
  (3) 5+5
  (4) 10  
With 1 coin being the minimum amount.
