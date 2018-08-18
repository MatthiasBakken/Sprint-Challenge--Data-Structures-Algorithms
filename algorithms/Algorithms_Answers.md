Add your answers to the Algorithms exercises here.

Exercise I

a. O(log(n))
b. O(log(n))
c. O(n^3)
d. O(n^2)
e. O(n^4)
f. O(1)
g. O(log(n))


Exercise II

a. Given an array a of n numbers, design a linear running time algorithm to find the maximum value of a[j] - a[i], where j ≥ i.

b. Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg is broken if it is thrown off floor f or higher, and unbroken otherwise. Devise a strategy to determine the value of f such that the number of dropped eggs is minimized.


Exercise III

function quicksort(array)
   if length(array) <= 1
       return array
   select and remove a pivot element pivot from array
   create empty lists less and greater
   for each x in array
       if x <= pivot then append x to less
       else append x to greater
   return concatenate(quicksort(less), list(pivot), quicksort(greater))

a. Suppose we implement quicksort so that the pivot is always chosen to be the first element of the array. What is the running time of this algorithm on an input array that is already sorted? Why?

b. Suppose we implement quicksort so that the pivot is always magically chosen to be the median element of the array. What is the running time of this algorithm? Why?