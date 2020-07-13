# Get Ahead - Interview Practice 1

## Flattened Iterator

### Problem Statement
Given a list of iterators, implement a `FlattenedIterator` class which incrementally iterates over the integers from all the iterators in an interleaved fashion. 

#### Test Cases
```sh
Iterators[0] = [1,2,3]
Iterators[1] = [4,5]
Iterators[2] = [6,7,8]

FlattenedIterator = [1, 4, 6, 2, 5, 7, 3, 8]
```

An iterator implements the `next()` and `hasNext()` interface. You're free to use them, and you will implement them on the `FlattenedIterator` class.
 
You're free to initialize `FlattenedIterator` with any data structure of your choice for the iterators.

### Testing
An important part of solving any technical problem is testing it. Remember to test not only the most generic cases, like the one presented in the example, but also various corner cases. Test your code thoroughly before calling it complete. During an interview, it is often a good idea to define the test cases before even starting the implementation. This not only shows a solid problem-solving approach, but might even help you find ideas for an optimal solution.
