#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n)

The runtine complexity of this code snippet is O(n). This is because the runtime will grow linearly as the size of n grows, (i.e., the while loop will run n times). This is because a is accumulating a sum of n*n, therefore you need n number of n*n before the loop will stop.


b) O(n log n)
The outer loop here is O(n) runtime, but the inner loop is O(log n) runtime since j is growing exponentially and the loop will stop when j reaches n. 


c) O(n)

This is O(n) runtime because the number of operations will increase linearly with the bunnies input number.

## Exercise II


Start by going to the middle floor and throw an egg off it.

If the egg breaks, go to the floor between the current floor and the bottom floor then throw another egg.

If the egg breaks, again go to the floor between the current floor and the bottom floor.

If the egg does not break go to a floor between the current floor, and the next highest floor where the egg broke. 

Repeat this until the next lowest floor where an egg broke and the current floor are next to each other.

This would be runtime complexity of O(log n) as it is a binary search strategy. Another strategy would be to go to each floor one by one and throw an egg off until you reached the floor where an egg cracks (linear search strategy O(n))
