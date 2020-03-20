#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This code run time will be O(n). This code will keep on running until the while loop is false. this loop will become n^2 after each loop as the a value keep on increasing.

b) This code would be O(n^2) because it is a nested loop. AS the n value increases, the time for running this loop will also increase by 2.

c) This code run time will be O(2n) because it is a recursive function. It will keep on running until the recursive function has reached its base value, and then has to add everything up after finding the base value of 0.

## Exercise II

1 write a function that will take the n-story buillfing number
2 divide the n-story num by 2
3 write a while loop that will keep on ruuning low of 0 and hight of len(n)
4 check if the egg break on middle floor
5 if yes, return the n
6 if no, next step
7 check if the egg break from the base to middle of n-story of the building
6 if does retunr the n number and break
7 next step
8 check if the egg break from the middle to len(n) of n-story of the building
9 if yes, retunr the n and break

this is like a binary search, so it ia divide and conquer pseudocode. which has a run time of O(lon n)
