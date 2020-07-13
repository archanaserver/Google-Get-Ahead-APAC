# GetAhead - Interview Practice 5

## Word Hunting

### Problem Statement
Given a `4X4` grid of letters and a dictionary, find the longest word from the dictionary that can be formed in the grid. 
The rules for forming a word are: 
* Start at any position on the board
* Move in any of the up to 8 directions to choose another letter
* Repeat
* Words must be at least 3 characters long
* You cannot reuse a letter in a given position in the same word. 
You are given a dictionary, with two helper functions: `isWord()` to check if a word is valid and `isPrefix()` to check if a string is a prefix of some valid word.


#### Example

For the grid on the left, the longest word is **FAMES**, for the one on the right, it is **EMBOLI** (note that there might be more than one solution, for example on the left **EMBOLI** is also valid, and same length):

![wordHunting_example1](https://user-images.githubusercontent.com/32739028/87285841-a4515480-c515-11ea-8452-1ee242bf2521.png) ![wordHunting_example2](https://user-images.githubusercontent.com/32739028/87285848-a61b1800-c515-11ea-989f-43b175d04d42.png)


### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
