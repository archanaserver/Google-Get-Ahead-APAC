# GetAhead - Interview Practice 6

## Car Plates Vocabulary

### Problem Statement
We need to find the shortest word from a vocabulary that includes all the letters from a given licence plate. The shorter the word, the better. The licence plates start with two or three letters, then they are followed by 5 characters, from which at most 2 are letters, the rest are digits.

Write a solution that will find the shortest words for 1000 licence plates. 

You are given a vocabulary containing all valid words. 

* Keep duplicate letters
* Ordering is irrelevant
* Case is irrelevant
* The vocabulary is sorted lexicographically
* The vocabulary contains about 4 million entries


#### Example: 

For the licence plate RT 123SO the shortest word would be SORT:

<p align="center">
    <img src="https://user-images.githubusercontent.com/32739028/87286567-a23bc580-c516-11ea-8465-b41adc432e08.png">
</p>


For RC 10014 the shortest word would be CAR.

<p align="center">
    <img src="https://user-images.githubusercontent.com/32739028/87286573-a536b600-c516-11ea-96f9-d101129e3d6c.png">
</p>

### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
