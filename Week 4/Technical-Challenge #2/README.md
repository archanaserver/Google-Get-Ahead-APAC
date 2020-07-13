# GetAhead - Interview Practice 2

## Balanced Parentheses

### Problem Statement
Given a string of parentheses, find the size of the longest contiguous substring of balanced parentheses. Parentheses are considered balanced when there is a valid closing parenthesis for an opening one.

#### Test Cases 

In this string: `())(())`, the longest continuous set would be 4 characters long (the last 4 characters of the input):

![balancedParanthesis_example1](https://user-images.githubusercontent.com/32739028/87285562-46247180-c515-11ea-9321-3e64c29a3dd7.png)

For `)(()))))((((()` , the max length would be 4:

![balancedParanthesis_example2](https://user-images.githubusercontent.com/32739028/87285566-47559e80-c515-11ea-8927-e9297e9116c7.png)

### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
