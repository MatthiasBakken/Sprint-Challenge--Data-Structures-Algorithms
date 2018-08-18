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

a. 
sorted_arr = sorted(arr)
return sorted_arr[-1] - sorted_arr[0]

b. I would do a mix of binary search and closest pair. Because the goal here would be not just to find where the egg is safe, but how high you can go until it breaks. So we would want to minimize the search area with a binary search algorithm but then identify the floor above as either a break or safe.

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