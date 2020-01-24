##### Please add your answers to the **_Analysis of Algorithms_** exercises here.

### Exercise I

a)
O(n). Since it is a loop. Time complexity grows in the while loop which is the value of a.

b)
O(n^2). Since it has 2 iterators. We first get n, and the outer loop is going to run 'n' time regardless of what happens in the inner loop. Then in the inner loop, the number 'j' that has to reach the value of 'n' loops which grows.

c)
O(n). Since it's recursion, as long as their is a base / return value it doesn't allow any infinite loop.

### Exercise II

### PLANNING

1. Check the floor that is halway up if it breaks.
   ### (start + end) // 2
2. if it breaks, then take all of the floors from 1 up to the middle floor.

3. if it doesn't break, check the halfway floor between the one. Then, checked the top floor.

### PSEUDOCODE

- a function accepts a sorted array and a value
- create a left pointer at the start of the array, and a right pointer at the end of the array
- While the left pointer comes before the right pointer: - create a pointer in the middle - if you find the value you want, return the index - if the value is too small, move the left pointer up - if the value is too large, move the right ointer down
- if you never find the value return -1

### COMPLEXITY

- O(log(n)) --> Binary search
