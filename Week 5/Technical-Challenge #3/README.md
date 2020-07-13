# GetAhead - Interview Practice 3

## Longest Path in Tree

### Problem Statement
Write a function that computes the length of the longest path of consecutive integers in a tree. 
 
A node in the tree has a value and a set of children nodes. A tree has no cycles and each node has exactly one parent. A path where each node has a value 1 greater than its parent is a path of consecutive integers (e.g. 1,2,3 not 1,3,5).
 
A few things to clarify:
Integers are all positive
Integers appear only once in the tree


#### Test Cases 

Note that there may be other valid answers.
For the tree on the left, the length of the longest path is 2, for that on the right, it's 4

![longestPath_example1](https://user-images.githubusercontent.com/32739028/87284742-58ea7680-c514-11ea-94c5-ee6247e19e9e.png) ![longestPath_example2](https://user-images.githubusercontent.com/32739028/87284749-5a1ba380-c514-11ea-9bd8-90681e2b593b.png)

### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
