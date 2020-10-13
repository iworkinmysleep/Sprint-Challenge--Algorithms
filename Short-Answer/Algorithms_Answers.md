#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
This will be O(n) because the function runtime grows at the same rate as the input.

b) 
This will be O(nlog(n)) because the runtime of the for loop grows at the same rate as the input and the second while loop grows at a slower rate than it's input.


c)
This will be 0(n) because the function is being called the number of times it takes to reach the base case of 0

## Exercise II
A binary search could be used for this problem. The highest floor plus the lowest floor divided by 2 would be the middle floor.  Drop the egg from the middle floor.  If it breaks, decrease the height in proportion to the lower floor until the egg is safe.  It the egg does not break, increase the height in proportion to the upper floor until the egg breaks.

Runtime is O(log(n)) because of the elimination of half of the floors.



