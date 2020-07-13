# GetAhead - Interview Practice 4

## Histograms and Areas

### Problem Statement
Given an array of non-negative integers that represent the bars (y value) in a histogram (with the array index being the x value), find the rectangle with the largest area under the curve and above the axis. Return the pair of array indices that represent the rectangle.

#### Test Cases 

Note that there may be other valid answers.
For array `[2,4,2,1]`, the largest area is 6, with height 2, and width from indices 0 to 2:

![histogram_example1](https://user-images.githubusercontent.com/32739028/87285213-df9f5380-c514-11ea-9283-d9454d9243f2.png)

For array `[2,4,2,1,10,6,10]` the largest area is 18, with height 6 and width from indices 4 to 6.

![histogram_example2](https://user-images.githubusercontent.com/32739028/87285220-e0d08080-c514-11ea-8451-240d2f16ba0a.png)


### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
